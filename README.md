# RATB_PWN
Automatically modify ratb mfd card dumps.

## Summary ##
Regia Autonomă de Transport București (RATB) is a public transport operator in Bucharest, Romania.

This tool automates the process of manually modifing mfd card dump files, which can be obtained with mfoc from all RATB cards after all keys have been recoverd, to set any desired number of travels.

This tool works on all Active green cards.

## RATB_PWN Usage ##
Run `./ratb_pwn.py -h` to show the help menu, or `./ratb_pwn.py ACTION -h` to show help for a specific action.

### Info ###
Run ratb_pwn with the 'info' action argument to list various relevant information about an mfd dump.

Example:

`./ratb_pwn.py info`

`./ratb_pwn.py info FILE`

### Mod ###
Run ratb_pwn with the 'mod' action argument to modify the dump file with the specified number of travels.

Example:

`./ratb_pwn.py mod`

`./ratb_pwn.py mod FILE TRAVELS`

`./ratb_pwn.py mod FILE TRAVELS -w`

## Resources ##
[RST Forums](https://rstforums.com/forum/topic/102403-nfc-challenge/) - Parsing hex data from mfd dumps

## LEGAL NOTICE ##
THIS SOFTWARE IS PROVIDED FOR EDUCATIONAL USE ONLY! IF YOU ENGAGE IN ANY ILLEGAL ACTIVITY THE AUTHOR DOES NOT TAKE ANY RESPONSIBILITY FOR IT. BY USING THIS SOFTWARE YOU AGREE WITH THESE TERMS.
