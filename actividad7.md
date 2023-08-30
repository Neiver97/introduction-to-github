function fn() {
 
var env = karate.env;
 
karate.log('karate.env system property was:', env);
 
if (!env) {
 
env = 'dev';
 
}
 
var config = {
  urlBase : 'https://test-dev.apps.ambientesbc.com'
 
};
 
if (env == 'dev') {
 
config.urlBase  = 'https://test-dev.apps.ambientesbc.com';
 
} else if (env == 'cer') {
config.someUrlBase = 'https://test-qa.apps.ambientesbc.com';
 
}
 
karate.configure('connectTimeout', 5000);
 
karate.configure('readTimeout', 5000);
 
karate.configure('ssl', true);
 
return config;
 
}
