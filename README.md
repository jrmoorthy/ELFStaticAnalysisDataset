# ELFStaticAnalysisDataset
Please cite the following paper if you found this useful - 

**Automated Static Analysis of Linux ELF Malware: Framework and Application**

Linux malware Static analysis dataset of ELF header features (approximately 20,000 ELF malware binaries from VirusShare).

Features include : multiple rows for a binary (one row for each section/segment)

binary anme, architecture,	endian,	class	type,	

num_sections,	section_hdr_size,

num_segments	segment_hdr_size,

num_import_funcs,	num_export_funcs,	num_libraries

is_pie,	is_stripped,	

has_nx,	has_notes,	

header_type	name,	size,	vsize	

entropy (section/segment)

perm_read,	perm_write,	perm_exec,	perm_none (permissions of the section/segment)
![image](https://github.com/user-attachments/assets/72466fc8-aa71-4280-9f44-d3e25a644b5b)


No. of binaries in for each architecture is as follows:

arm	  6946

i386	3269

m68k	1686

mips	3966

ppc	  1764

sh	  1762

sparc	1294

x86	  1052

Hashes of the malware as specified by Virusshare is included binary name in the dataset e.g., Virusshare_<hash>_<arch>.

The architecture is also appended to the name of the binary.

More details can be found in the research paper.


