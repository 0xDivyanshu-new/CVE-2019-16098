# CVE-2019-16098

This CVE exploits the RTCore64.sys driver and creates a cmd.exe process with system privileges by copying the token of the System process with one of the low-privilege cmd.exe process.

Blog about the approach and the methodology can be found [here](https://divyanshu-mehta.gitbook.io/researchs/windows-security-research/exploit-development/rtcore64.sys-cve-2019-16098).
