LWP::ConnCache::Resolving can be used to add resolution to LWP::ConnCache.

It might be useful if you have multiple hostnames that result in the same logical connection which can be interchangably used for all of them (either have the same IP address or connect to the same farm of load balanced servers, for example).

Module itself does not define a resolution mechanism leaving it to the user to define (I'll probably write DNS resolver as pre-canned module in the future) - see resolver constructor parameter.