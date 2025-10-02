Validate IP Address
Given a string queryIP, return "IPv4" if IP is a valid IPv4 address, "IPv6" if IP is a valid IPv6 address, or "Neither" if IP is not a valid IP of any type.

A valid IPv4 address is an IP in the form "x1.x2.x3.x4" where 0 <= xi <= 255 and xi cannot contain leading zeros.
A valid IPv6 address is an IP in the form "x1:x2:x3:x4:x5:x6:x7:x8" where 1 <= xi.length <= 4 and xi is a hexadecimal string.

Example 1:
Input:

queryIP = "172.16.254.1"

Output:

"IPv4"

Explanation: This is a valid IPv4 address, each section is between 0 and 255, and there are no leading zeros.

Example 2:
Input:

queryIP = "2001:0db8:85a3:0000:0000:8a2e:0370:7334"

Output:

"IPv6"

Explanation: This is a valid IPv6 address.

Example 3:
Input:

queryIP = "256.256.256.256"

Output:

"Neither"

Explanation: In this case, some sections are larger than 255, so it is not a valid IPv4 address.

Constraints:
queryIP consists only of English letters, digits, '.', and ':'.