# Adaption Of Firmwalker ( Hitwords )
# Hitwords

Quick Moddified version for command based usage and a few little extras
( could be beefed up more to incorpoate statistic counts and such) 

A simple bash  script for searching the extracted or mounted firmware file system.

It will search through the extracted or mounted firmware file system for things of interest such as:

## Usage


								      			(hitword/*)###Pattern File Sets Search Params!!!!
	-qd     Quick Search Firmware Directory For Word 					(Search Param)
	-qf     Quick Search Firmware File For Word 	 					(Search Param)
	-d      Search Firmware Directory for Pattern in files 					(hitword/dir)
	-f      Search Firmware File for Pattern 					 	(hitword/file)
	-fm     Show More Around Those Patterns in Firmware File 			 	(hitword/file)
	-qfm	Quick Show More around Word in Firmware file				 	(Search Param)
	-qdm	Quick Show more Around Word Firmware Directory For Word				(Search Param)
	-fwc	Search Word In Directory And Show File type and hashes				(Search Param)
	-lwc	Search For Word In Directorys then Read Out Elf Info/ Links Based on Word	(Search Param)
	-s      Search For Files With extensions in Firmware Directory				(hitword/ext)
	-p     	Search For Password Files in Firmware Directory					(hitword/passfile)
	-pr	Search For Password Files in Firmware Directory and Read			(hitword/passfile)
	-coms	Search for patterns matching comms list in files				(hitword/comms)
	-conf  	Search for config files in directory 						(hitword/conffiles)
	-ssl	Search and list all SSL related keys/hashes					(hitword/sslfiles)
	-b	Search for important binaries							(hitword/binaries)
	-md5    Search for MD5 hashes in files							(use -fwc)
	-pem	Read Out Pem files from Directory						(Only Directory)
	-crt	Read Out CRT files from Directory						(Only Directory)
	-key	Read Out KEY files from Directory						(Only Directory)
	-sh	Perform *.sh file search in directory						(Only Directory)
	-bin	Perform *.bin file search in directory						(Only Directory)
	-ip	Search for ip addresses in files						(Only Directory)



### Firmwalker Script created by Craig Smith and expanded by:
* Athanasios Kostopoulos
* misterch0c
* Frank Sx ( Hitwords )
### Links
* https://craigsmith.net
* https://woktime.wordpress.com
* https://www.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=Firmware_Analysis
* http://frankhacks.blogspot.com.au/

