# 2.1.0
 - added option to configure polling frequency and number of messages to fetch in one batch to be able to manage AWS SQS cost

# 2.0.0
 - added support for Logstash 6.x.

# 1.0.3
- added some metadata to the event (bucket and object name as commited by joshuaspence)
- also try to unzip files ending with ".gz" (ALB logs are zipped but not marked with proper Content-Encoding)

# 1.0.2
 - fix for broken UTF-8 (so we won't lose a whole s3 log file because of a single invalid line, ruby's split will die on those)

# 1.0.1
 - same (because of screwed up rubygems.org release)

# 1.0.0
 - Initial Release
