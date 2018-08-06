# Office-Scan

Batch scan your documents to jpeg files using the command line.

## Requirements

- Linux/Unix OS
- a scanner!
- libsane
- sane-utils
- imagemagick


## Installation

	npm install -g office-scan

## Usage
	office-scan -o [OUTFILE] OPTIONS

	OPTIONS:

	  -n=number of pages          (default = 1)
	  -p --paper=paper type       (default = "white") Can be one of "dark", "white"
	  -c --color                  If set a color scan will be done. By default scans are monochrome.
	  --dpi=dots per inch         (default = 150)
	  -d --device=device to use   (default = 1) Index of the device to use. Display list of devices using -l
	  -l --list-devices           Lists all attached devices
	  --pdf                       Convert to pdf
	  --noscan                    Do not scan (use to compile a PDF of previously scanned images)
