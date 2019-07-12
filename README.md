# zca_customer
caricatore customers

This program has as input an excell file structured like "test_program.xls"

fills internal tables of program "RFBIDE00" (declaration lines 25-47) dynamically using field names.
for each line of the excell file fills a group of structures, and then writes them into a txt file, that get passed to the program "RFBIDEK0".
