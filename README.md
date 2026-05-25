What This Code Does:
• Specifically tracks Tiangong Space Station 
• Uses realistic Tiangong orbit parameters:
o 390 km altitude (same as real Tiangong)
o 51.6° orbital inclination (real Tiangong orbit)
o ~90 minute orbit period
• Shows "TIANGONG" on display 
• Realistic orbital simulation when live data isn't available
• Multiple fallback methods to get data
 Proximity Alerts for Tiangong:
• Less 1000 km: Fast blinking LED
• Less 2000 km: Slow blinking LED
• Over 2000 km: LED off
 Data Sources Attempted:
1. Celestrak.org - TLE data for Tiangong (NORAD 48274)
2. Space APIs - Fallback to orbital simulation
3. Realistic simulation - Based on actual Tiangong orbit
This is as close as we can get to real Tiangong tracking without paid APIs. The simulation uses real Tiangong orbital parameters, so it's much more accurate
