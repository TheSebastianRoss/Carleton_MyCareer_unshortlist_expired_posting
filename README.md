# Carleton_MyCareer_unshortlist_expired_posting

## Problem description:
- Job postings on Carleton University's MyCareer website can be saved to a "shortlist"
- Once such postings expire, the shortlist button disappears
- The unshortlist button also disappears
- Therefore if you shortlist a job and you don't decide to apply to it before the deadline expires, then the job is stuck on your shortlist.

## Solution description:
- The website uses the same code for every unshortlist button; the only thing you need to change in the code is the job ID
- It is possible to gut the unshortlist button from another posting and insert its contents into another button on a different page
- It is possible to use the information on the page to automatically determine the job ID without the user needing to enter it in manually
- It is possible to put the code into an single expression and remove the requirement for a button entirely

## Usage
- Go to the job listing page for the particular expired job you want to unshortlist
- Copy the code in unshortlist.js to your clipboard
- Open the developer console in your browser
  - Chrome: ctrl + shift + J / cmd + opt + J
  - Firefox: ctrl + shift + K / cmd + opt + K
  - Microsoft Edge and Internet Explorer: f12, then go to the console tab
  - Safari: cmd + opt + C
  - Opera: ctrl + shift + I / ⌘ + ⌥ + I
- Paste it in to the console
- Press enter
  - Warning! Executing someone else's code you don't understand in your console can be dangerous! (What? You really think someone would just go on the internet and tell lies?)
- Refresh your shortlist
- Watch in awe as you see that your job has disappeared!
