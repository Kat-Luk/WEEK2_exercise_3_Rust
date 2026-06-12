Task 3

In this task, you make a new public module with a public function and use it in another file, the main.rs file.
Make a new folder called "new_module" in the src folder. Make mod.rs file and new_file.rs. Make new_file a public module in the mod.rs file. In file new_file.rs, make a public function called calling_from_far() that prints "Hello! I am speaking to you from another file!" and returns 1.

Import "new_module" into main.rs and use new_file from new_module.
Call the function calling_from_far in the main.rs file.

Example run:

Hello! I am speaking to you from another file!
