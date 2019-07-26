websocket - Tiny, cross platform websocket client C library.
Features
No additional dependecies
Single header library interface librws.h with public methods
Thread safe
Send/receive logic in background thread
Example
Create and store websocket object handle
  // Define variable or field for socket handle
  rws_socket _socket = NULL;
  ............
  // Create socket object
  _socket = rws_socket_create();
