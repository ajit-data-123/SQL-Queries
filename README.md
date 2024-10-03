# SQL-Queries
I am a biggener in data analysis.
I have started learning SQL, R and Python.

-- Check for NULL values in any COLUMN
SELECT COUNT(*) 
FROM "202301-divvy-tripdata"
WHERE ride_id IS NULL
	OR rideable_type IS NULL
	OR started_at IS NULL
	OR ended_at IS NULL
	OR start_station_name IS NULL
	OR start_station_id IS NULL
	OR end_station_name IS NULL
	OR end_station_id IS NULL
	OR start_lat IS NULL
	OR start_lng IS NULL
	OR end_lat IS NULL
	OR member_casual IS NULL ;
	

