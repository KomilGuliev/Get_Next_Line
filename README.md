# Get_Next_Line

The project is analogous to the getline function in C++.
The function allows the following:
- Reading a line by a file descriptor
- Managing multiple file descriptor
  - (*Example: if the file descriptors 3, 4 and 5 are accessible for reading, then you can call
  get_next_line once on 3, once on 4, once again on 3 then once on 5 etc. without
  losing the reading thread on each of the descriptors.*)
