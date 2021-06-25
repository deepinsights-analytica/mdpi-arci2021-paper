# Condition Monitoring of Drive Trains by Data Fusion of Acoustic Emission and Vibration Sensors

### Oliver Mey, André Schneider, Olaf Enge-Rosenblatt, Dirk Mayer, Christian Schmidt, Samuel Klein and Hans-Georg Herrmann

This GitHub repository is part of a paper submission to the MDPI Journal *Processes*, Special Issue *Process Control and Smart Manufacturing for Industry 4.0* (see https://www.mdpi.com/2227-9717/9/7/1108).

*(Please be patient. This repository is under construction.)*

The complete dataset is available via the Fraunhofer Fordatis database (http://dx.doi.org/10.24406/fordatis/132). It contains the measured raw data (data/<measurement>/<sensor>.csv) as well as metadata that describes the vibration and acoustic emission sensors (sensors/<sensor>.json) and the configuration of all measurements (measurements/<measurement>.json). A total of 29 measurements are included. For each measurement the the file vb.csv contains the vibration data: a timestamp in the first column followed by 8192 sensor values.  It is sampled with a sampling rate of 8192 Hz. One line thus corresponds to a measurement time of one second. The ae.csv files with the acoustic emission data also contain a timestamp in the first column followed by 8000 sensor values. It is sampled at a sampling rate of 390625Hz. One line therefore corresponds to a measurement time of 20.48 ms. A file w.csv with the speeds was also recorded for each measurement. These files contain the time frames (begin and end timestamp) for the five rotational speeds: 600rpm, 1000rpm, 1400rpm, 1800rpm, 2200rpm). While the measurement for the vibration and the acoustic emission was carried out continuously for the different speeds, the phases with an almost constant speed can be extracted with the help of the time ranges based on the w.csv files.






