# RSA Breach 2011

## Company Background

RSA is a company that provides security products and services for their customers, headquartered in Massachusetts in the US. One of the famous products from the company is SecureID. SecureID enables employees to connect to their internal services with two-factor authentication using one-time passcode (https://whatis.techtarget.com/definition/RSA-Security). And it is also famous for the security breach around SecureID that happened in 2011.

## Two most significant aspects of the breach

Normally when a breach happens, victim companies notice the breach after the attack is finished. However, the breach was detected while the attack is in progress by its internal security team (Eric Chabrow, 2011 April). And this contributed in reducing the size of the ramification of the breach.

Although RSA’s security practice in terms of monitoring and responding to the on-going attack positively shows its ability to handle and recover from security incidents, the outcome of the breach was still severe. The company lost four customers after the breach, and customers raised concern and elevated their expectation on RSA’s security infrastructure. And as a result, RSA hired a CSO in June 2011 (Tom Brewster, 2012)

## What happened with the breach?

As a result of the security breach, the seed values of SecureID have been compromised (Ars Staff, 2011). SecureID secure token product is basically worthless if its algorithm and seed values are leaked. Hackers can generate any client’s one-time passcode if they know the client’s seed value. Hence, in order to mitigate the attack, RSA decided to replace the clients’ secure tokens. However, RSA claimed the attack was mainly targeted at the defense sectors and government-related organizations, and only clients within those categories will be provided with the replaced secure tokens, for example Lockheed Martin.

## How/why did it happen?

The attack pattern was identified as APT (advanced persistent threat) where a team of hackers initiates and executes an attack with long-term presence in a very specific target’s system. The attack initially leveraged social engineering by targeting an employee at RSA. The employee got a phishing email, and the click of the phishing email launched the attack in the employee’s machine. The attack vector’s payload contained a zero-day vulnerability of Adobe Flash, and it installed a trojan program called Poison Ivy. And the attack was able to make lateral movement within the system and attempted to gain privilege escalation. And it turned out the attack eventually succeeded and extracted data from the RSA system to an external server using FTP (John Leyden, 2011). However, while the attack is in progress, the internal security team, Incident Response Team, identified abnormal activities within the system, and in the middle of the attack, the company could block the attack and was able to reduce the size of damage (Eric Chabrow, 2011 April).

The attack could have been prevented effectively if the company had measures on how long an account logged in a system or when the account logged in. For example, while the privilege escalation is attempted, the attacker should use an account to log in and get in to the system, if any monitoring system could have detected an abnormal login time or login duration, the company would have acted on the attack before it actually compromised the system.

## Timeline of major events pre and post breach discovery.

The breach was discovered by the RSA’s security team and publicly announced on March 17th 2011. Below is the brief timeline of the attack (UKEssays, 2018):

- After 2011, February 28th:
  - An attacker acquired zero-day vulnerability of Adobe Flash The attacker sent phishing emails with an Excel file composed of the Adobe Flash zero-day vulnerability and Poison Ivy Trojan to RSA employees. An employee became a victim of the phishing attack, and it opened up the way for the  attack to the RSA’s network system. The attacker got credentials to go deep down in the RSA’s internal system using privilege escalation attacks. The attacker moved data from a server that contains data related to SecureID to an internal server where the data was aggregated, compressed and encrypted for extraction. The attacker used FTP to extract the encrypted data from the RSA’s internal server to an external server and the encrypted data was removed to hide the evidence of the attack.
- On 2011, March 14th:
  - Adobe issued a security advisory and shared the patch schedule for the Adobe Flash zero-day (https://www.adobe.com/support/security/advisories/apsa11-01.html).
- On 2011, March 17th:
  - RSA announced the discovery of the security breach happened for SecureID.
- On 2011, March 21th:
  - Adobe released the patch for the zero-day vulnerability.
- On 2011, June 6th:
  - RSA publicly announced the offer of replacement of victim clients’ secure tokens.

## What were the direct costs (expenses) of the breach? 

As a consequence of the security breach happened in RSA infrastructure, the company had to pay $66.3 million (Eric Chabrow, 2011 August). And that cost included the replacement of secure tokens for its clients, attack investigation, hardening security infrastructure such as monitoring and IT systems. 

What were the business impacts of the beach event in terms of lost revenues, stock prices, and company reputation? Were the executives held liable (fired or did they step down)? Has the company since recovered? 

It was obvious that the security breach caused damage to the business. However, RSA regained its business stance quickly. The business expanded in the second quarter by 13 percent. And the year-to-year growth for the first quarter was 8 percent (Eric Chabrow, 2011 August).

The company’s reputation has been affected at the beginning. However, from the fact that the company was able to identify the attack in progress by their own security team, it positively showed that RSA’s security infrastructure can protect and recover from cyber attacks. Hence, even if some clients left after the breach and the attack was mainly targeting the defense sector, Lockheed Martin still keeps business relationships with RSA.

Also, a year later RSA’s chairman, Art Coviello, said that the company no longer is dealing with the security breach (Tom Brewster, 2012).

## References

Eric Chabrow (2011, April 4). ‘Tricked’ RSA Worker Opened Backdoor to APTI Attack. Bank Info Security. Retrieved from https://www.bankinfosecurity.com

Tom Brewster (2012, February 29). RSA: Back from the breach? ITPro. Retrieved from https://www.itpro.com

Ars Staff (2011, June 6). RSA finally comes clean: SecureID is compromised. Ars Technica. Retrieved from  https://arstechnica.com

John Leyden (2011, April 4). RSA explains how attackers breached its systems. The Register. Retrieved from https://www.theregister.com

UKEssays (2018, November). RSA SecureID Breach Overview and Prevention Strategies. Retrieved from https://www.ukessays.com

Eric Chabrow (2011, August 1). RSA Breach Costs Parent EMC $66.3 Million. Bank Info Security. Retrieved from https://www.bankinfosecurity.com
