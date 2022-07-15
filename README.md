# algofi-scripts
Useful scripts for the Algofi Protocol.

## Status
This repo is undergoing continuous development.

## Start
`virtualenv venv`

`pip3 install -r requirements.txt`

## Generate health ratio report + save to disk
`python3 run_liquidate_report_from_state.py --health_ratio_threshold 0.85 --borrow_threshold 1.0 --html_fpath /path/to/file`

## Generate health ratio report + email
`python3 run_liquidate_report_from_state.py --health_ratio_threshold 0.25 --borrow_threshold 0.1 --email email@email.com`

## Generate liquidated users report + save to disk
`python3 liquidation_actions_report.py --block_delta 4000 --html_fpath /path/to/file`
