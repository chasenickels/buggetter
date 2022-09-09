# buggetter

### Usage:
#### To Create:
##### Usage: buggetter --create --os *operating system* --version *OS version* --product *product the bug pertains to* --summary *summary of issue* --description *more detailed summary of bug*
##### Ex: buggetter --create --os redhat --version 8.6 --product red hat enterprise linux 8 --summary iptables in new AMI is the wrong version --description The iptables package should be 1.8.4, but is currently 1.8.3
#### To List:
##### Usage: buggetter -l *operating system*
##### Ex: buggetter -l redhat
