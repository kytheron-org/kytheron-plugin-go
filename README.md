# Kytheron Plugins 

## Source plugins 

Connect to and stream from a source, and emit parseable logs 
- Tailing files
- Streaming CloudWatch / Cloudtrail logs 

## Parser

Receive streamed logs from source plugins or elsewhere
and converts them to a Kytheron standard structure

- Access Logs 
- SystemD Logs 
- Cloudtrail / Cloudwatch 
- Kubernetes 

## Output 

Plugins that receive Kytheron events, and emit those to 
specified endpoints, such as Jira, Pagerduty, Slack, Email, etc