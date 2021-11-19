---
layout: post
title: Flux calibration in TESS
---

TESS will take (and save) Full Frame Images at 30 minute cadence for their entire mission. However, like Kepler (and K2), the TESS pipeline will provide a differential photometry data product. i.e. the data is *not* flux calibrated.

The Guest-Investigator (GI) program for TESS does provide a level of funding for software projects if they are doing something value-added and unique for the community. Flux calibration should be very doable, given the FFI's.

The question I see (and without enough knowledge of the TESS detector and hardware) is this:
**What are the calibration frames that are required to do this?**. Put another way, what *could* Kepler have done to accomplish this?


### Some relevant literature:

- [Bryson et al. (2010)](http://adsabs.harvard.edu/abs/2010ApJ...713L..97B)
- [Hogg et al. (2013)](http://adsabs.harvard.edu/abs/2013arXiv1309.0653H)
  - and associated GitHub [repository](https://github.com/davidwhogg/SaveKepler)
- [Stubbs et al. (2016)](http://arxiv.org/abs/1601.04052)