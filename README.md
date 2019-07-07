# salahtime-go

salahtime-go is a small command line application written in Go that displays the Islamic prayer times for Europe/Copenhagen. It uses a slice to store the Europe/Copenhagen time table and the table can easily be substituted for another city.

salahtime-go automatically detects if daylight saving (CEST) is on and compensates by adding an hour to each prayer time in the table.

The Europe/Copenhagen prayer time table is based upon observation, yet it does not take into account changes during the twilight season (late April until early August). For that period the time is calculated using the most precise method.

## Installation

Clone this repository and use `go install` to build and install the application. Run it with `salahtime-go`.

If you use Arch Linux you can also install salahtime-go via [AUR](https://aur.archlinux.org/packages/salahtime-go).
