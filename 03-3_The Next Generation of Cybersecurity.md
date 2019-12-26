### Steps of Zero Trust
##### ZTA requires three fundamental steps, applied at the level of applications and services within the network:
##### 1. Verify the user (authentication, part 1)
##### 2. Verify the device (authentication, part 2)
##### 3. Verify access privileges (authorization)
##### These three layers of verification are accomplished through a series of compliance checks based on the characteristics of each. 
##### These compliance checks can include information ranging from device encryption to user patterns of behavior, and can continue to expand as more information about users and devices is collected.
##### Failing any of these checks will label the user or device as “non-compliant” and deny access to that user or device.
##### While it is optimal to maintain a common set of compliance checks across a network and organization using modernized software systems, it is still possible to implement this critical piece of zero trust into networks that are dispersed and use legacy hardware and software, as in the case of DoD.
##### DoD Service-or agency-specific applications and systems can be built to have their own compliance checks, driving all users and devices that interface with them to adhere to those rulesets.
##### This in turn can influence users and devices outside the orbit of those Services/agencies, which must similarly comply with those requirements to gain access.
##### In this way, a ZTA can act as a virus (albeit a secure, trustworthy virus), “infecting” third party users or devices by forcing them to meet compliance standards if they hope to gain access.
##### This in turn will make it easier for those third parties to eventually implement zero trust into their own applications and services, as they will already have certain standards of compliance on which they can build. Compliance metrics can (and should) be iterative.
##### ZTA can begin with a set of modest identity and device health checks, then develop a more sophisticated set over time depending on the sensitivity of the applications and services in question and the desired restrictions on access.
##### Each “generation” of compliance checks will have the ability to add more nuance to access control as more information about users and devices is collected, building a more comprehensive digital picture of them.
##### These checks will ensure not only the identity, but the integrity of users and devices: while identity checks will map the characteristics of each, integrity checks can run health diagnostics on devices to look for compromise.
##### If a device has the 
