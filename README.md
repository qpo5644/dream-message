# dream-message
Message systems like Disque allow communication between processes using different queues. So a process can send a message to a queue with a given name, and only processes which fetch messages from this queue will return those messages. Moreover, multiple processes can listen for messages in a given queue, and multiple processes can send messages to the same queue.
