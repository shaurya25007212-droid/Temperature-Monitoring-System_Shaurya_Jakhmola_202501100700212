Temperature Monitoring System
📌 Case Study Title
Temperature Monitoring System

📝 Problem Statement
- Build a Python program to display messages according to the temperature received from an assumed IoT system.
- Accept maximum and minimum temperature limits from the user.
- Generate random temperature values at every 2-second interval.
- Compare the generated values with the limits and display appropriate messages.

⚙️ Approach
- Input Handling: The program accepts minimum and maximum temperature limits from the user.
- Random Temperature Generation: Using Python’s random.randint(), values are generated within a range slightly beyond the limits (±10).
- Condition Checking:
- If the temperature is below the minimum → Display "Temperature too low!"
- If the temperature is above the maximum → Display "Temperature too high!"
- Otherwise → Display "Temperature is normal."
- Looping & Delay: The program runs continuously with a 2-second delay (time.sleep(2)) to simulate real-time monitoring.
