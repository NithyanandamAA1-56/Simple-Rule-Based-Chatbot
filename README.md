Input Normalization: The line user_input = input("👤 You: ").lower() converts the user's text to lowercase. This is a basic form of text preprocessing, ensuring the rules match regardless of capitalization (e.g., "Hello" vs. "hello").
Rule-Based Matching:It uses if, elif (else if), and else statements.
The condition checks use in (e.g., "hello" in user_input), which is a form of simple pattern matching. It looks for specific keywords or phrases within the entire input string.
Conversation Flow: The chatbot is enclosed in a while True loop, allowing for a continuous conversation until the user explicitly triggers the exit condition (break).
Fallback: The final else statement provides a default response when no predefined rule is matched. This is crucial for a smooth user experience, preventing the bot from crashing or giving a blank reply.# Simple-Rule-Based-Chatbot
