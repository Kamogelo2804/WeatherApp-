ST10454876 - Kamogelo Monnakgotla
# WeatherApp-
This app allows you to access the weather for the week and a specific day

I have made an app that allows you to see the weather for the week and also alows you to see the weather for a specific day this was done through the use of Android studio. I used relevant code and the use of arrays and loops to make the app, I ensured that the interface was user friendly and was easy to read.
The purpose of the is to allow users to see the weathe forecast for the week it reveals the minimum and the maximum temperature for the day. To make the app I utilized the following psuedocode to make the app run:

Start 
    Display "Welcome to Weather App"

    // Declarations
    daysOfWeek = {"Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"}
    minTemps = {55, 60, 58, 57, 59, 61, 62}
    maxTemps = {75, 78, 80, 76, 77, 79, 81}
    weatherConditions = {"Sunny", "Cloudy", "Rainy", "Stormy", "Windy", "Foggy", "Snowy"}
    averageTemps

    Call mainFunction()

Main Function:
    Repeat:
        Display menu options:
            1. View weather for a specific day
            2. View weather for all days
            3. Exit

        Get user choice

        Switch user choice:
            Case 1:
                Call viewWeatherForSpecificDay()
            Case 2:
                Call viewWeatherForAllDays()
            Case 3:
                Call stop()
            Default:
                Display "Invalid choice. Please try again." message

    Until user chooses to exit the program

Stop Function:
    Display "Thank you for using Weather App"
    Terminate the program

ViewWeatherForSpecificDay Function:
    Prompt "Enter the day of the week"
    Get user input for day

    If day is valid:
        Display weather information for the specified day
    Else:
        Display "Invalid day. Please try again." message

ViewWeatherForAllDays Function:
    Display header: "Day", "Min Temp", "Max Temp", "Avg Temp", "Condition"

    For each day in daysOfWeek:
        Display day, minTemp, maxTemp, averageTemp, and weatherCondition

End

