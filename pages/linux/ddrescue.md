# ddrescue

> Data recovery tool that reads data from damaged block devices.
> More information: <https://www.gnu.org/software/ddrescue/manual/ddrescue_manual.html#Invoking-ddrescue>.

- Take an image of a device, creating a log file:

`sudo ddrescue {{/dev/sdb}} {{path/to/image.dd}} {{path/to/log.txt}}`

- Clone Disk A to Disk B, creating a log file:

`sudo ddrescue {{[-f|--force]}} {{[-n|--no-scrape]}} {{/dev/sdX}} {{/dev/sdY}} {{path/to/log.txt}}`
