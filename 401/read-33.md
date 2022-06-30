# Learning CompleteableFuture
-- -
-- -

## ComputableFuture Class
-- - 

### Asynchronous Computation in Java

    Computation, in general, is based on a series of steps.  
    Asynchronous Computation: actions represented as callbacks tend to be either scattered acrouss the code or deeply nested inside each other.  

### Using *ComputableFuture* as a Simple *Future*

ComputableFuture class implements Future interface. 

    Ex: 
        we can create an instance of this class with a no-arg constructor to represent some future result, hand it out to the consumers, and complete it at some time in the future using the *complete* method.  
        The consumer may use the  *get* method to block the current thread until this result is provided. 

Below we have a method that creates a CompletableFuture instance, then spins off some computation in another thread and returns the Future immediately.  

    Ex: 
        public Future<String> calculateAsync() throws InterruptedException {
                CompletableFuture<String> completableFuture = new CompletableFuture<>();

                Executors.newCachedThreadPool().submit(() -> {
                    Thread.sleep(500);
                    completableFuture.complete("Hello");
                    return null;
            });

            return completableFuture;
        }

To spin off the computation, we use the Executor API. This method of creating and completing a CompletableFuture can be used together with any concurrency mechanism or API, including raw threads.

Note: The calculateAsync method returns a Future instance. 

We simply call the method, receive the Future instance, and call the *get* method on it when we're ready to block for the result.

Also observe that the *get* method throws some checked exceptions , namely ExecutionException(encapsulating an exception that occurred during a computation)and InterruptedException(an exception signifying that thread executing a method was interrupted):  

    Ex:
        Future<String> completableFuture = calculateAsync();

            // ...

        String result = completableFuture.get();
        assertEquals("Hello", result);

-- -
-- -

Source: [Guide To CompletableFuture](https://www.baeldung.com/java-completablefuture)