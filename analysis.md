# Task 3 - fixed-window reliability review (replace four lines)
SLI: (10,000 - 120) / 10,000 x 100 = 98.80% for 2026-10-01T00:00:00Z/2026-10-30T00:00:00Z,
below the agreed 99.0% SLO.
Allowed errors: 10,000 x (1 - 99.0/100) = 100 requests.
Remaining error budget: allowed errors - actual errors = 100 - 120 = -20 requests.
Decision: prioritize reliability work before routine feature releases because the remaining error budget is negative.