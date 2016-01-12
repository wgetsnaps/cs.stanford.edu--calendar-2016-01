# Snapshot of Stanford CS Calendar


You can view the mirrored version by visiting this URL:

http://wgetsnaps.github.io/cs.stanford.edu--calendar-2016-01/events/calendar/month/2016-01.html


This repository is a mirror of the following site:

|     Key     |                          Value                           |
|-------------|----------------------------------------------------------|
| Site title  | Events Calendar January 2016                             |
| Publisher   | Stanford Computer Science                                |
| URL         | http://www-cs.stanford.edu/events/calendar/month/2016-01 |
| Mirrored at | 2016-01-11 22:25:31                                      |



# Wget/Bash used

~~~sh
wget  --recursive \
      --level 1 \
      --no-host-directories \
      --adjust-extension \
      --convert-links \
      --page-requisites \
      --output-file /dev/stdout \
      http://www-cs.stanford.edu/events/calendar/month/2016-01 |
      tee -a ./wget.log
~~~
