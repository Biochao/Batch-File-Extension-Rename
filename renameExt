import os

# Set the directory where the files are located
root_directory = 'romfs folder'

# Traverse the directories and rename the files
for root, dirs, files in os.walk(root_directory):
  # Loop through each file in the directory
  for file in files:
    # Get the file name and extension
    file_name, file_ext = os.path.splitext(file)
    print(file_name)

    # Check if the file has the extension you want to rename
    if file_ext == '.tranm':
      # Rename the file with the new extension
      os.rename(os.path.join(root, file), os.path.join(root, file_name + '.gfbanm'))
