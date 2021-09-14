

# 1000 Days of Code Daily Updates Journal
**Contains personal notes of 1000 days of code learning**

**Started at Day 25 as previous days have just been summarized in Twitter**

 ## Day 25 - Malware Static Analysis
- **Static Analysis** - The process of analyzing a computer program without running.
- **Anti-Virus Programs** rely mainly on database of *file signatures* as well as *heuristics*.
- **File Signatures** - Identifiable piece of known suspiscious code.
- **Heuristics** - Behavioural and pattern matching analysis.
- **Hashing** - program fingerprints, used to produce a unique hash that is used to identify a program.

- **Hash usage:**
	- Use the hash as a label.
	- Share the hash with analyst to identify a malware.
	- Search for the hash online to see if a malware has already been identified.
- **Common hash functions in malware analysis:** 
	1. The Message-Digest Algorithm MD5 is the most commonly used for malware analysis.
	2. Secure Hash Algorithm 1 (SHA-1) is also popular.
	
- **Finding Strings**
- **Packed and Obsfucated Malware**

 ## Day 26 - byteCode to String formating tool
- **aLIEz** - started developing a tool called *aLIEz* that will auto format program strings references with readibility in mind. This is meant to be used in static analysis for reverse engineering.
- **Electron** - decided to use electron for *aLIEz* since its based on web technologies. Having a lot of problems currently, will continue to resolve in the upcoming days.
