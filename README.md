# Guessing.md
flowchart TD;
    Start[Start] --> InputRange[Input Min and Max Range];
    InputRange --> GenerateNumber[Generate Random Number within Range];
    GenerateNumber --> OutputNumber[Output the Random Number];
    OutputNumber --> End[End]
    graph TD;
    Start[Start] --> InputRange[1 and 20];
    InputRange --> GenerateNumber[Generate Random Number within Range];
    GenerateNumber --> OutputNumber[Output the Random Number];
    OutputNumber --> End[End]
    Copy the flow chart and enter a random number ranging from 1-20. the flow chart will in return try to guess your number.
