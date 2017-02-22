### Telemetry and event ingestion

* Telemetry or *"distant measurement"* can mean *lots of events*
* Modest logistics example: 
 * A fleet of 300 vehicles with location data transmitted twice a minute
 * 36,000 events per hour
 * About a million events per day—too much for a database-backed application
 * Historically, complex operations at DB level to partition, thin and purge samples


