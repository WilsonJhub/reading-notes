# Spring MVC and Thymeleaf

-- -

**Spring Model Attribute** 
- Spring MVC calls the pieces of data that can be accessed during the execution of views model attributes.The equivalent term in Thymeleaf language is context variables.  
  - _Add_ model attribute to Spring MVC:
    - model.addAttribute
  - Return ModelAndView with model attributes included:  
    - ModelAndView mav = new ModelAndView("message/list");  
        - mav.addObject("messages", messageRepository.findAll());  
          - return mav;
  - Expose common attributes via methods annotated @ModelAttribute:  
    - @ModelAttribute("messages")  
       public List<Message> messages() {  
       return messageRepository.findAll();  
    }
-- -
Source:  
- [Spring MVC and Thymeleaf](https://www.thymeleaf.org/doc/articles/springmvcaccessdata.html)