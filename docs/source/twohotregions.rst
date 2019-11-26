.. module:: xpsi.TwoHotRegions

.. _twohotregions:

TwoHotRegions
=============

Instances of :class:`~.TwoHotRegions.TwoHotRegions` are represent pair of
radiatively intense regions of the source photosphere. The class inherits
from :class:`~.HotRegion.HotRegion`, and applies the methods to compute photon
pulses from a pair of spots which may be related under some model; useful for
pulsars under the assumption of a dominantly dipolar magnetic field with two
magnetic polar caps. The regions must share a parameterisation, but not
parameters; the regions do not need to be related via antipodal reflection
symmetry.

.. autoclass:: xpsi.TwoHotRegions.TwoHotRegions
    :members: embed, integrate, print_settings, num_params, bounds, cellArea
    :show-inheritance:

.. autoclass:: xpsi.TwoHotRegions.PulseError
    :show-inheritance: