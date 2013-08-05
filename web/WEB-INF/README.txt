The special configuration files required for the application, including the web application
deployment descriptor (web.xml), tag library descriptors for custom tag libraries that we have
created, and other resource files we wish to include within the web application.  Even though this
directory appears to be a subdirectory of your 'document root', the Servlet Specification prohibits 
serving the contents of this directory (or any file it contains) directly to a client request.  
Therefore, this is a good place to store configuration information that is sensitive (such as
database connection usernames and passwords), but is required for the application to operate 
successfully. 