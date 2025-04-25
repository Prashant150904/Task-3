 Overview
This project provides a MySQL database schema for tracking Royal Challengers Bangalore (RCB) players in the Indian Premier League (IPL). It includes player statistics, auction details, and performance metrics, optimized for efficient querying and analysis.
Key Features
✅ Structured Player Data – Batting, bowling, and contract details
✅ JSON Support – Track seasons played using JSON arrays
✅ Optimized Indexes – Faster queries with composite and functional indexes
✅ Analytical Queries – Pre-built queries for performance insights
✅ Active Player View – Simplified access to current squad stats
Database Schema:
Table: rcb_players
Column	Type	Description
player_id	INT	Unique player identifier
player_name	VARCHAR(100)	Full name of the player
role	ENUM	Player role (Batsman, Bowler, etc.)
nationality	VARCHAR(50)	Player's country
seasons_played	JSON	Array of seasons (e.g., ["2023", "2024"])
runs_scored	MEDIUMINT	Total runs scored
batting_avg	DECIMAL(6,2)	Batting average
strike_rate	DECIMAL(6,2)	Batting strike rate
wickets_taken	SMALLINT	Total wickets taken
bowling_avg	DECIMAL(6,2)	Bowling average
auction_price	DECIMAL(8,2)	Price in crore (₹)
current_status	ENUM	Active, Retired, Released, etc.
Summary:
This database helps analyze RCB's squad composition, player retention, and value-for-money performance. Ideal for cricket analysts, team management, and fantasy sports enthusiasts!
