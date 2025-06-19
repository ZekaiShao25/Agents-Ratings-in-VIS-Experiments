# Timeline

## Information

| Paper Title (with link)                                                                                           | Authors   | Venue     | OSF Repo Link |
|--------------------------------------------------------------------------------------------------------------------|-----------|-----------|----------------|
| [Evaluating the Effect of Timeline Shape on Visualization Task Performance](https://dl.acm.org/doi/10.1145/3313831.3376237)                                    |Sara Di Bartolomeo , Aditeya Pandey , Aristotelis Leventidis , David Saffo , Uzma Haque Syeda , Elin Carstensdottir , Magy Seif El-Nasr , Michelle A. Borkin , Cody Dunne           |ACM CHI           |<https://osf.io/qr5yu/>                |

## experiment_code.ipynb

1. If you want to run our code, please install the dependencies according to `requirement.txt` and fill in your openai key first.
2. In the part of **Related Functions**, we provide some functions that will be used later, if you don't need to know the exact implementation, the function name is all you need.
3. In the part of **Prompt Preparation**, we provide all the prompts that will be used later. All variable names in prompts are capitalized. If you wish to learn more about the specifics of the prompts we design, you can peruse this section.
4. In the part of **Data Preparation**, we show how to get the required data and images from the experimental materials folder `./experiment_material`. If you wish to replace the data with your own, check the type of the original data first and make sure that your data and the original data type are identical.
5. In the part of **Task Execution**, we show how to combine prompts and data to accomplish tasks. The experiment logs will be stored in a file named `timeline.json` in the same directory.
