This is a demonstration of the use of R to build QR codes for various purposes. While there are many ways that QR codes can be generated, R has the advantage of enabling the user to produce these codes in large quantities with many variations, quickly and easily, and at no additional cost to the organization. Many free and paid apps are available for use on modern smartphones that can be used to scan these codes.
Note that the placement of logo overlays needs to be adjusted based on the output medium (e.g., html, word, png, etc.). The script is presented optimized for word output.
For the purpose of reproducibility, a sample data frame is included (inputCSV.rds). In the script, replace the code read.csv("QRcodeInput.csv", stringsAsFactors = FALSE) with readRDS(“inputCSV.rds").
