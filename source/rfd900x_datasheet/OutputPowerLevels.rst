Output power levels
===================================================

Many countries have different legal power levels. Be sure to operate
within the legal power limits of the country that you are operating in.
The RFD900x modem can support the power levels between 0dBm and 30dBm in
1dBm steps. :eq:`power` can be used to convert the power in dBm into
milliwatts.

.. math::
  :label: power

  P_{mw}= 10^{P_{dBm}/10}

To calculate Effective Isotropic Radiated Power (EIRP) you can use :eq:`eirp` below:

.. math::
  :label: eirp

  EIRP(dBm)=P_{transmit}(dBm)-P_{cableloss}(dBm)+G(antenna)(dBi)

The FCC limit for EIRP is 4 Watts, or 36dBm for frequency hopping radios
in the ISM 900 MHz band.  The Australian EIRP limit is 30dBm as defined by ACMA.