# OTP_bruteforce_payloads
4, 5, and 6 digit OTP payloads for bruteforcing OTP and rate limit testing vulnerable apps

Command used to create payload is
echo -e {0000..9999} | sed 's/ /\n/g' >> output_filename.txt

sed is used to remove new lines and spaces
