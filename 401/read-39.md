# Location
-- -

## Get the last know location


### Create Location Services Client  

`In your activity's onCreate() method, create an instance of the Fused Location Provider Client as the following code snippet shows.`  

    private FusedLocationProviderClient fusedLocationClient;

        @Override
        protected void onCreate(Bundle savedInstanceState) {

        fusedLocationClient = LocationServices.getFusedLocationProviderClient(this);
    }