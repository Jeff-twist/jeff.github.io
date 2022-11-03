# MARATHON-DATA-PROJECT
This project is about Berlin marathon from the year 2009 to 2019, it contains information about the runners, time they took to complete the race and the yearly weather condition.

I did a little research on the best weather for running and how weather affects marathon races, I discovered that the best tempearture to run a fast marathon is between 10⁰C to 17⁰C any hotter than that, and things can go south.

I imported the Marathon and weather data which I had already saved to my computer to Jupyter notebook with the use of Python libraries(OS and Pandas). With the use of Pandas, I did Data exploration and cleaning such as;
- Removing duplicates
- Renaming some values in a particular column, to match the others
- Changed the column data types
- Removed some empty rows
- Removed outliers
- Renamed a column on the second table to enable merging of both tables
- Merged both tables

After Exploration and cleaning, I created a Dataframe to hold information of winners per year seperately for both genders. I then used it to create a visualization using Matplotlib and Seaborn showing;
- Yearly winners for each Genders
- Age of winners per year
- Age that has the most wins
- Details of the 2019 winner

From the output of the charts I discovered that the best performance for both genders came in the year 2018 where the temperature was about 15⁰C and the lowest was in the year 2009 which had a temperature of 16.5⁰C. So it's safe to say that, Temperatures between the range of 13⁰C and 15⁰C brought out the best in the athletes.

While working on this project I got to learn more Data exploration and cleaning techniques to enable me filter my Data to be more presentable and flexible.

I also learned the impact of weather in marathon races and the best weather temperature for a favorable race.
