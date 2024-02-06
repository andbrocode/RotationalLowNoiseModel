This document provides information on the provided data. 

There is one **.csv** file with comma separated data columns and a **.pkl** (pickle) file.

Headers explained:

- **index**:  row index
- **period**:  period in seconds [s]
- **frequency**:  frequency in hertz [Hz]
- **rlnm_rot_rate**: the RLNM inferred from the NLNM by Petersen (1993) [rad^2/s^2/Hz]
- **rhnm_rot_rate**:  the RHNM inferred from the NHNM by Petersen (1993) [rad^2/s^2/Hz]
- **nlnm_acc**:  the NLNM by Petersen (1993) for accelerations [m^4/s^4/Hz]
- **nhnm_acc**:  the NHNM by Petersen (1993) for accelerations [m^4/s^4/Hz] 
- **gsn_horizontal_acc**:  the GSN based Low Noise Model for horizontal accelerations by Berger et al. (2004) [m^4/s^4/Hz]
- **gsn_vertical_acc**:  the GSN based Low Noise Model for vertical accelerations by Berger et al. (2004) [m^4/s^4/Hz]
- **gsn_vertical_rot_rate**:  the RHNM inferred from the model for vertical components by Berger et al. (2004) [rad^2/s^2/Hz]
- **gsn_transverse_rot_rate**:  the RHNM inferred the model for horizontal components by Berger et al. (2004) [rad^2/s^2/Hz]
