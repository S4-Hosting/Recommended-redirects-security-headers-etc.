# Recommended .htaccess additions (for WP and most sites)

Security Headers, etc. can be set at apache config levels or at .htaccess level for individual sites. 

These are our recommended .htaccess additions for non-SSL to SSL redirect, enabling HSTS and setting basic security headers, if they are not set at the server config level. 

Note: If you are using an OpenLiteSpeed server then security header rules in .htaccess are ignored and you will need to add them in OLS Webadmin - see https://github.com/S4-Hosting/receommended-.htaccess-additions/blob/master/OLS

*Note: The 'Permissions Policy' header is a replacement for the 'Feature Policy' header which will be deprecated. We have included both as browser support for Permissions Policy is very low (as of 02/21).*

*Note: We've also added interest-cohort=() to ther Permissions Policy header as an opt-out of FLoC - see more about FLoC here: https://scotthelme.co.uk/what-the-floc/ *
