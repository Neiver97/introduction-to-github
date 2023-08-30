function fn() {
 
var env = '#{env}#';
 
karate.log('karate.env system property was:', env);
 
if (!env) {
 
env = 'dev';
 
}
 
var      = {
       : 'https://test-dev.apps.ambientesbc.com'
 
};
 
if (env == 'dev') {
 
config.      = 'https://test-dev.apps.ambientesbc.com';
 
} else if (env == 'cer') {
config.      = 'https://test-qa.apps.ambientesbc.com';
 
}
 
karate.configure('       ', 5000);
 
karate.configure('       ', 5000);
 
karate.configure('ssl', true);
 
return config;
 
}
