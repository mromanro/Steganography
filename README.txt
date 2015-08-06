Project Description:
This package is for the program Steganography. Its purpose was to create a graphical user interface
that allowed the user to hide a secret message within a cover image. Through composing the two
images together, the user is able to send secret messages within plain site. A user is also able to
retrieve secret messages from images.

Purpose/Background:
The Steganography project was a school assignment for Software Engineering Principles 1. The
total team size consisted of seven members.

Understanding and navigating this package:
      DesignDocumentation: contains files explaining our code, requirements, process, and reasoning.
	..\Steganography\Documentation\Design 	      - All information regarding design.
	..\Steganography\Documentation\Misc   	      - All information that is miscellaneous.
	..\Steganography\Documentation\Requirements   - All information regarding requirements.

      ImgGrpN_Steganographer: contains everything related to the actual source code and build of the project.
	Node: See below for package specification and location of the code related files.

Known Issues:
      - Because the image is saved as a JPEG, there is an issue with retrieving the secret image. JPEGs cut
        off some bits.
      - Some error handling issues. When the user attempts to save or load and cancels, there appears to be an issue.

/********Project Information*********************************************************************************************/

Current Status of Project: On-Hold

Current Mission: 
Refactoring
 fixing the 2 currently known bugs
JUnit test for more bug issues.

Programming Language: Java 1.8, JavaFX

IDE: NetBeans 8.0.1

Tools Used: JavaFX SceneBuilder 2.0

Package format of ImgGrpN_Steganographer: Netbeans standard package
	Source code is located in: 	..\Steganography\ImgGrpN_Steganographer\src
	Build script is loated in:	..\Steganography\ImgGrpN_Steganographer
	The build dependancys are in: 	..\Steganography\ImgGrpN_Steganographer\nbproject
	Class files is loacted in:	..\Steganography\ImgGrpN_Steganographer\build\classes\imggrpn_steganographer
	Jar files are located in:	..\Steganography\ImgGrpN_Steganographer\dist


