phpBB Forum Archiver
=

Introduction
-
This tool browses a phpBB forum (following links by HTTP GET requests) and saves all the threads where a given user contributed in the HTML format.
It also saves locally all css/js resources and parses-adapts all references to them.

Usage
-

- Run the *.exe file
- Indicate a forum user nickname
- Entering a pause between requests may help circumventing with requests timeout resrictions (100ms default usually works)
- Enter a list of thread to exclude (Long & useless threads can be skipped)
- Enter the output directory where all HTML & resources files will be saved.
- Click the Go! button (execution time depend on the number of pages to browse, which depends on the number of messages the user posted)

Warning
-
Execution time may be non-negligeable, especially for a high number of thread pages to archive. Use the Task Manager if you need to kill the process.
Legal notice: This program is provided as-is without any warranty, any user is responsible for its use, and the creator shall not be liable for any damages done to any information system as a result of its use.