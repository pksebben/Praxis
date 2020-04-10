# 0.00_BM-XX-XX_SECURITY
This unit is actually kind of a test-case for a format of breadcrumb.  See note META FORMATTING below for more information

# META FORMATTING
So when looking at making this breadcrumb, an issue made itself apparent; what is the scope of this crumb?

I thought of doing it on firewalls at first, or perhaps on linux security in general, and thought that hey, wouldn't it be great to just do it on hacking in general?

So here's the scrub for this problem; Now that I have optics on this issue of scoping in a more concrete manner, I want to implement a fractal structure for these breadcrumbs.  What this means is, that I am starting with the broadest possible scope and immediately drilling down to the most specific and encapsulated scope where a breadcrumb is still going to be useful.  I will be starting this particular breadcrumb with firewalls.

The structure, then, looks thus:
Security \ Networking \ Firewalls
(this may or may not be the optimal amount of granularity.  Some sort of function to make this flexible should be baked in.)
