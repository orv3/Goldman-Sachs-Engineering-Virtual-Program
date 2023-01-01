# Goldman Sachs Engineering Virtual Program

## Analyze and Propose uplifts to controls and policies 

### Background Information

As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. To be successful at your job you often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

## Task / Objective

Your job is to crack as many passwords as possible with available tools (e.g. use Hashcat) and determine the following: 

```
1) What type of hashing algorithm was used to protect passwords?
2) What level of protection does the mechanism offer for passwords?
3) What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?
4) What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?
5) What would you change in the password policy to make breaking the passwords harder?
```
### Observation

Hashlist: All the hashes (19) are in user : hash form and are hashed by MD5 algorithm as per my analyzation.
```
experthead:e10adc3949ba59abbe56e057f20f883e
interestec:25f9e794323b453885f5181f1b624d0b
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4
reallychel:5f4dcc3b5aa765d61d8327deb882cf99
simmson56:96e79218965eb72c92a549dd5a330112
bookma:25d55ad283aa400af464c76d713c07ad
popularkiya7:e99a18c428cb38d5f260853678922e03
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98
liveltekah:3f230640b78d7e71ac5514e57935eb69
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b
johnwick007:f6a0cb102c62879d397b12b62c092c06
flamesbria2001:9b3b269ad0a208090309f091b3aba9db
oranolio:16ced47d3fc931483e24933665cded6d
spuffyffet:1f5c5683982d7c3814d4d9e6d749b21e
moodie:8d763385e0476ae208f21bc63956f748
nabox:defebde7b6ab6f24d5824682a16c3ae4
bandalls:bdda5f03128bcbdfa78d8934529048cf
```

Cracked Password: The cracked list (19/19 cracked) is in the form of user : hash : pass 
```
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4:qwerty
flamesbria2001:9b3b269ad0a208090309f091b3aba9db:Flamesbria2001
bookma:25d55ad283aa400af464c76d713c07ad:12345678
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c:password1
simmson56:96e79218965eb72c92a549dd5a330112:111111
interestec:25f9e794323b453885f5181f1b624d0b:123456789
spuffyffet:1f5c5683982d7c3814d4d9e6d749b21e:Spuffyffet12
oranolio:16ced47d3fc931483e24933665cded6d:Oranolio1994
liveltekah:3f230640b78d7e71ac5514e57935eb69:qazxsw
johnwick007:f6a0cb102c62879d397b12b62c092c06:bluered
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b:Pa$$word1
experthead:e10adc3949ba59abbe56e057f20f883e:123456
popularkiya7:e99a18c428cb38d5f260853678922e03:abc123
reallychel:5f4dcc3b5aa765d61d8327deb882cf99:password
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759:1234567
bandalls:bdda5f03128bcbdfa78d8934529048cf:Banda11s
moodie:8d763385e0476ae208f21bc63956f748:moodie00
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98:password!
```

### Conclusion

A through report has been sent to the organization which includes the observation and a breif analyzation of the level of protection offered by implemented controls and minimize the probability of a successful breach. The report can be found [here](https://github.com/orv3/Goldman-Sachs-Engineering-Virtual-Program/blob/a378bd58b644f83ee3aaa17ff479c764748742bc/REPORT%20GOLDMANN%20SACHHS%20VIRTUAL%20PROGRAM.docx) for review. 

### Resources

1) https://hashcat.net/hashcat/
2) https://resources.infosecinstitute.com/topic/hashcat-tutorial-beginners/
3) https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/
