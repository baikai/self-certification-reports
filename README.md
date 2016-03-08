# ODPi self-certification reports

This repository consists of the ODPi compliance test run results made by ODPi Compliant Distributions. ODPi compliant distrubutions can issue pull requests against this repo to publicize thier self-certification to the ODPi specifications.

## How to report self certification

1. Download the latest acceptance test suite from http://repo.odpi.org/repository/ODPi/1.0/acceptance-tests/
2. Unzip the test package on the primary machine on your Hadoop cluster you wish to test.
3. Run the tests
4. If the test pass, issue a pull request with the XML output in a file using the naming convention: $HADOOP_VERSION-$OS-$ARCH-$SPECVERSION.xml to this repository.
5. A member of the ODPi will review and merge in.
