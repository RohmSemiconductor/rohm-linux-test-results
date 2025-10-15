# Automated Linux driver test results
This repository holds test results of automated Linux driver test system.
<br>
🔗[Accelerometer results](https://github.com/RohmSemiconductor/rohm-linux-test-results/tree/Sensor)
- KX022ACR-Z
- KX132ACR-LBZ

🔗[PMIC results](https://github.com/RohmSemiconductor/rohm-linux-test-results/tree/PMIC)
- BD71815
- BD71828
- BD71837
- BD71847
- BD96801
- BD9576

<br>
🔗[ADC/DAC results](https://github.com/RohmSemiconductor/rohm-linux-test-results/tree/ADDAC)
- BD79703

## About
Linux mainline kernel includes thousands of changesets per development cycle. Kernel version 6.12 received 13355 changesets from 
2074 developers between 15 September and 17 November in 2024. That equates to around 210 changesets per day. The Linux 
kernel is where the drivers reside and is also where the changes happen that can negatively impact the driver functionality. The large 
amount of changesets and time required for validation makes manual testing impractical. An Automated test system offers an efficient
solution to find regressions early and identify the changeset that introduces regression.
<br> <br>
This repository holds the results produced by automated Linux driver test system. The results are visible for 30 days.
<br> <br>
The results are organized in three branches [Sensor](https://github.com/RohmSemiconductor/rohm-linux-test-results/tree/Sensor), [PMIC](https://github.com/RohmSemiconductor/rohm-linux-test-results/tree/PMIC), and [ADDAC](https://github.com/RohmSemiconductor/rohm-linux-test-results/tree/ADDAC). The branches hold result in directories, and one directory holds the results of a single test run. Detailed results are only written of tests that found failures. Overall results of the test run can be found in summary.txt, and component specific results can be found in a component specific directories. Serial communication logs are available in the \*\_UART\_LOG files.
<br><br>
The result directories are named in the following manner:<br>
YYYY_MM_DD_hhmmss_*Linux branch*_*PASSED/FAILED* <br>
