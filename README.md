# An Updated Characterization of Erratic Pixels in HST WFC3 IR

We search for erratic pixels in WFC3 IR using dark frames, which are ideal for this purpose, with simple structure and low count rates for high sensitivity. After removing images taken within one hour of South Atlantic Anomaly passage, we have 177 darks from 2017 (117 when comparing against Hilbert 2012). We model the flux value in each pixel's time-series as a Gaussian mixture model.

## Getting Started

At the minimum, the model script expects an input pickle file containing a data cube of the dark images and the corresponding errors.

### Prerequisites

This project requires python 2.7 along with numpy. The sampling is done with pystan.

