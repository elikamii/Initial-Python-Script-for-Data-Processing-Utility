# Initial-Python-Script-for-Data-Processing-Utility
# data_processor.py

def read\_and\_print\_file(file\_path):
"""Reads a file and prints its content line by line."""
try:
with open(file\_path, 'r') as file:
print(f"--- Reading content from: {file\_path} ---")
for line in file:
print(line.strip())
print("------------------------------------------")
except FileNotFoundError:
print(f"Error: The file '{file\_path}' was not found.")
except Exception as e:
print(f"An unexpected error occurred: {e}")

if **name** == "**main**":
\# Assume 'sample\_data.txt' exists in the same directory
"""Reads a file, prints its content, and calculates the total word count."""
