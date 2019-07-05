# salahtime

Salahtime is a small command line application written in Go that displays the Islamic prayer times for Europe/Copenhagen.

Salahtime uses a slice to store the Europe/Copenhagen time table and the table can easily be substituted for another city.

Salahtime automatically detects if daylight saving (CEST) is on and compensates by adding an hour to each prayer time in the table.

## Installation

Clone this repository and use `go install` to build and install the application. Run it with `salahtime-go`.
