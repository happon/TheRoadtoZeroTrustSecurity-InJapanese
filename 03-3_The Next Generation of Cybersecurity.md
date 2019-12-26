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
##### If a device has the appropriate characteristics but demonstrates compromise (e.g., lack of encryption, virus infection), then the device will be deemed non-compliant and will be denied access.
##### One such identity check includes the management of certificates, which will help verify identity in ZTA by pairing public keys with the devices requesting access to an application or service.
##### While certificates on their own may be stolen or imitated, ZTA protects against this risk by including certificates and public keys as one attribute for users and devices that must be corroborated with multiple other attributes in order to authenticate and grant a request for access.
##### Additionally, certificates can be strengthened by including both user and device data into the certificate, requiring verification of both to enable access for either.
##### In advanced ZTA, this health inspection may ultimately be applied to the application or service being accessed
##### - once the access requester has been verified, the zero trust model might then query the access destination to ensure the security of that destination.
##### By transitioning from a “one-way handshake” to a “two-way handshake” model, an organization can better ensure that neither the users and devices nor the applications and services are compromised and infect one another.
##### More advanced forms of ZTA can also protect applications and services by applying microsegmentation to discrete areas within each application and service, building specific access rules for each of those areas.
##### This methodology would protect against adversaries that penetrated the network perimeter and the application or service itself, limiting the data access and maneuverability of those adversaries.
##### As in the case of microsegmentation at the application and service level, microsegmentation within those entities should require authentication and authorization specific to the subsegment in question, enabling a more precise “least-privilege access” model of security. 
