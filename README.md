# Mojo-EWS-Auth

This is a simple Mojo-lite app for logging into an EWS based system.

It provides a basic login form, an error page, and a landing page.

It checks for a configuration file which can contain:

- ews: the EWS url
- home: the page which a successful login redirects to

It relies on Mojo::UserAgent::LWP::NTLM, which lives [here](https://github.com/simonecesano/perl-Mojo-UserAgent-LWP-NTLM)

And that's it.
