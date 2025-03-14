# Daily Number Incrementer

A simple Python script that automatically increments a number in a text file and commits the change to git. Perfect for maintaining a daily commit streak or tracking sequential values.

## Setup

1. Clone this repository:

```bash
git clone https://github.com/georgewshen/new_fancy_job
cd new_fancy_job
```

2. Run the script:

```bash
python3 update_number.py
```

3. Setup a cron job to run the script daily:

```bash
crontab -e
```

Add the following line to the crontab file:

```bash
0 6 * * * cd /path/to/your/repo && python3 update_number.py
```

This will run the script at 6am every day.

## Usage

The script will increment the number in `number.txt` and commit the change to git. You can modify the script to increment by any value or use a different file to store the number.

By running this you will be able get a fancy streak on your github profile and get a job.

![How to get a job](get_a_job.jpg)
