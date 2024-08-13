How to Use the Script:
Prepare the Input File:

Create a file named ip_addresses.txt in the same directory as the script.
Add one IP address per line in this file.
Run the Script:

Ensure you have Python installed on your system.
Run the script using the command:
python pinger.py

The script will read the IP addresses from ip_addresses.txt, ping each address, and write the results to ping_results.txt.

Check the Output:
The results will be stored in a file named ping_results.txt, indicating whether each IP address was reachable or not.

Script Explanation:
ping_ip(ip): Pings the given IP address and returns True if reachable and False otherwise.

read_ips_from_file(input_file): Reads and returns a list of IP addresses from the specified input file.

write_results_to_file(results, output_file): Writes the ping results to the specified output file.

main(input_file, output_file): Orchestrates reading IPs, pinging them, and writing the results.

This script is a simple and effective way to automate the process of checking the reachability of multiple IP addresses and documenting the results.
