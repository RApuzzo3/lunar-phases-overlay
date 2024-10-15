Lunar Phases Overlay
Version: 1.0
Author: Rick Apuzzo
Date: October 2024
Description

The Lunar Phases Overlay is a Pine Script-based indicator for TradingView that visualizes the phases of the moon directly on your price chart. This script is designed for traders who are interested in exploring potential correlations between lunar cycles and market price movements.

The script displays labels for various lunar phases (such as New Moon, Full Moon, First Quarter, and Last Quarter) above the chart. Additionally, on the first bar of each month, it adds a label with the month name and year, displayed below the bar for easy reference.
Key Features

    Lunar Phase Labels: Moon phases, including New Moon, Full Moon, First Quarter, Last Quarter, and more, are shown at the top of each bar corresponding to the specific lunar phase.
    Monthly Labels: On the first day of each month, a label showing the month and year is placed below the bar.
    Timezone Configurable: A timezone_offset input allows users to adjust the indicator to match their local timezone.
    Histogram: A visual representation of the lunar phase percentage as a histogram below the chart.
    Optimized for Performance: The script supports up to 365 labels, ensuring it remains efficient even when applied to charts with extensive historical data.

How to Use

    Install the Script: Add the Pine Script code to your TradingView account.
    Configure Timezone: Use the timezone_offset setting to adjust the lunar phases for your local timezone.
    Apply the Script: The indicator can be applied to any trading chart, and it will automatically overlay the moon phases and monthly labels.
    Analyze: Explore potential relationships between the lunar cycle and market price action.

Installation

    Open your TradingView account.
    Navigate to the Pine Script Editor.
    Copy and paste the script provided in this repository into the Pine Script Editor.
    Save the script and add it to your chart by clicking Add to Chart.

Inputs

    Timezone Offset: An integer input that allows you to adjust the lunar phase calculations to match your local timezone. The default is set to 0, which corresponds to UTC.

Example

    Lunar Phase: Labels like 🌑 "New Moon", 🌕 "Full Moon" will appear at the top of the price bars.
    Month/Year Labels: On the first bar of the month, a label showing the month and year (e.g., September 2024) will appear below the bar, helping traders quickly orient themselves in time.

Configuration

You can adjust the timezone_offset to reflect your specific time zone. For example, if you live in a region that is 5 hours behind UTC, you would set timezone_offset to -5. This ensures that the lunar phases are aligned with your local time.

License

This project is licensed under the Mozilla Public License 2.0. See the LICENSE file for details.
Contact

If you have any questions or issues with the script, feel free to reach out via the GitHub Issues tab.
