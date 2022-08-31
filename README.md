- 👋 Hi, I’m @Parksiurn
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Parksiurn/Parksiurn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Android-PIN-Bruteforce (0.2) is used to unlock an Android phone (or device) by bruteforcing the lockscreen PIN.
  Find more information at: https://github.com/urbanadventurer/Android-PIN-Bruteforce

Commands:
  crack                Begin cracking PINs
  resume               Resume from a chosen PIN
  rewind               Crack PINs in reverse from a chosen PIN
  diag                 Display diagnostic information
  version              Display version information and exit

Options:
  -f, --from PIN       Resume from this PIN
  -a, --attempts       Starting from NUM incorrect attempts
  -m, --mask REGEX     Use a mask for known digits in the PIN
  -t, --type TYPE      Select PIN or PATTERN cracking
  -l, --length NUM     Crack PINs of NUM length
  -c, --config FILE    Specify configuration file to load
  -p, --pinlist FILE   Specify a custom PIN list
  -d, --dry-run        Dry run for testing. Doesn't send any keys.
  -v, --verbose        Output verbose logs

Usage:
  android-pin-bruteforce <command> [options]

