# bitcoin-price-alert

Polls a public Bitcoin price API and prints alerts when the price crosses
thresholds I set. I run this in a tmux pane and forget about it until
something moves.

## install

pip install -r requirements.txt

## usage

The first run with no saved state will create ~/.config/bitcoin-price-alert/
and a thresholds file. Edit that or use flags.

<!-- last-checked: 2026-10-05 -->
