# redirect-site &middot; [![Netlify Status](https://api.netlify.com/api/v1/badges/9727b20a-efc0-456e-9bde-6fc197a9085f/deploy-status)](https://app.netlify.com/sites/redirect-site/deploys)

[This site](https://p7x.me) redirects to my other sites and is built using [this repo](https://github.com/pr4shan7/redirect-site).

## What I learned

Being new to this, I initially struggled setting up this site so that it works as required. I was trying to setup a site which redirects to my other sites and uses secure `https` protocol. I did not have any hosting server so I could not install my SSL certificate. I did setup `301` redirects which worked pretty well, but they were not up to the mark.
I finally configured the server on _Netlify_, and now it works pretty well.

**Here's what I learned in the process:**

* Learned about and configured DNS settings, specifically `CNAME`, `ALIAS`, `A`, `AAAA` and `Redirect`, for my custom domain.
* Issued and setup an SSL certificate. (CSR, DCV)
* Learned about diferent types of redirects, viz. `301`, `302`, `404` and `200`.
* Migrated my _nameservers_ to and setup _Netlify_ via [this repo](https://github.com/pr4shan7/redirect-site).
* Learned about and configured `_redirects` file on _Netlify_ server.
* Learned about and setup `splat` parameter in `_redirects`. It was the thing that I was searching for.
