# MALDetect-Ensemble-Framework
Stacking Ensemble method for detecting Windows based malware binaries : EMBER and MOTIF Dataset
During the analysis and exploration of the Ember dataset,
the following features were examined:
1) label: Indicates whether the file is labeled as benign
(False) or malicious (True).
2) .textsize: Size of the .text section in the PE file
3) .textentropy: Entropy of the .text section in the PE file.
4) .textvsize: Virtual size of the .text section in the PE file
5) .datasize: Size of the .data section in the PE file.
6) .dataentropy: Entropy of the .data section in the PE file.
7) datavsize: Virtual size of the .data section in the PE file.
8) .rsrcsize: Size of the .rsrc section in the PE file.
9) .rsrcentropy: Entropy of the .rsrc section in the PE file.
10) .rsrcvsize: Virtual size of the .rsrc section in the PE file.
11) machine: Type of machine for which the file is intended.
12) subsystem: Target subsystem for the PE file.
13) generalsize: Size of the general file information in the
PE header.
14) generalvsize: Virtual size of the general file information
in the PE header.
15) generalhas debug: Indicates whether the PE file has a
debug section (True) or not (False).
16) generalexports: Number of exported functions in the PE
file.
17) generalimports: Number of imported functions in the PE
file.

18) generalhas relocations: Indicates whether the PE file has
relocation information (True) or not (False).
19) generalhas resources: Indicates whether the PE file has
resource information (True) or not (False).
20) generalhas signature: Indicates whether the PE file has a
digital signature (True) or not (False).
21) generalhas tls: Indicates whether the PE file has thread
local storage (TLS) information (True) or not (False)
22) generalsymbols: Number of symbols in the PE file.
23) stringsnumstrings: Number of printable strings in the PE.
24) stringsavlength: Average length of the printable strings
in the PE file.
25) stringsprintabledist: Histogram of printable characters
within the printable strings.
26) stringsprintables: Indicates whether the PE file contains
printable strings (True) or not (False).
27) stringsentropy: Entropy of characters across all printable
strings.
28) stringspaths: Number of strings that begin with ”C:”
indicating paths.
29) stringsurls: Number of strings that contain ”http://” or
”https://” indicating URLs
30) stringsregistry: Number of strings that contain ”HKEY ”
indicating registry keys.
31) stringsMZ: Number of strings that contain ”MZ” indicating Windows PE droppers or bundled executables.
32) cofftimestamp: Timestamp in the COFF header of the
PE file.
33) coffmachine: Target machine for which the PE file is
intended.
34) coffcharacteristics: List of image characteristics of the
PE file.
35) optionalsubsystem: Target subsystem specified in the
optional header of the PE file.
36) optionaldll characteristics: List of DLL characteristics of
the PE file.
37) optionalmagic: Magic value in the optional header of the
PE file

38) optionalmajor image version: Major image version specified in the optional header of the PE file.
39) optionalminor image version: Minor image version
specified in the optional header of the PE.
40) optionalmajor linker version: Major linker version specified in the optional header of the PE file.
41) optionalminor linker version: Minor linker version specified in the optional header of the PE file.
    
