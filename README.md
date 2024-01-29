# Planetary-Gear
Application for diagnosing the technical condition of a single-stage planetary gearbox based on the measurement of vibration acceleration and the rotational speed of the input shaft

A planetary gear is a type of gear transmission. It transmits a lot of power and consists of a ring, a solar wheel and a salt wheel.
The measuring station for this application consists of:
- EP 90/1C planetary gear
- immobilized, internally toothed rim
- reducer
- tachometer, 4 markers per revolution
- NI9234 measurement card
- acceleration sensor PCB 35608

Frequency characteristic of the gear:
- rotational frequency of the input shaft
- rotational frequency of the output shaft
- rotational frequency of the satellite wheels
- meshing frequency
- modulating frequencies

Application operation diagram:
-> Reference
Calculation of characteristic frequencies and orders
peak and amplitude detection
recording to TDMS
->diagosis
detection of peaks and their amplitudes in the analyzed signal
Comparison of the amplitudes of reference peaks with those detected in the analyzed signal
Information about exceedances
