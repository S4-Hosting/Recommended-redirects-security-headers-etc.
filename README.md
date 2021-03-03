# .htaccess additions for WordPress

Security Headers, etc. can be set at apache config levels or at .htaccess level for individual sites. 

These are our recommended .htaccess additions for non-SSL to SSL redirect, enabling HSTS and setting basic security headers, if they are not set at the server config level. 

Note: If you are using an OpenLiteSpeed server then security header rules in .htaccess are ignore - see https://github.com/S4-Hosting/htaccess-additions-for-wp/blob/master/.htaccess

Note: The 'Permissions Policy' header is a replacement for the 'Feature Policy' header which will be deprecated. We have included both as browser support for Permissions Policy is very low (as of 02/21).
