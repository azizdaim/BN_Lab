# BN_Lab: Bayesian Network Lab (Likelihood and Inference)

CS3081 · Artificial Intelligence · Lab 4

The notebook is in [`bn_lab.ipynb`](bn_lab.ipynb). Screenshots of the completed lab (20/20 correct) are below.

## 1. Reading the graph and building the network

Parents of Train, direct vs. indirect dependence, and how CPTs are built in pgmpy.

![Steps 1 and 2: reading the graph and building the network](lab4_screenshot_01.png)

## 2. Reading values from the CPTs

`check_model()` output and questions on the Maintenance and Train tables.

![Step 2: questions 3 to 5](lab4_screenshot_02.png)

## 3. Joint probability (likelihood)

P(r, m, t, a) = P(r) × P(m | r) × P(t | r, m) × P(a | t), with the example "no rain, no maintenance, train on time, you attend" = 0.3402.

![Step 3: questions 6 and 7](lab4_screenshot_03.png)

## 4. A bad day, and the start of inference

Heavy rain, maintenance, train delayed, you miss the appointment = 0.0024. Then observing that the train is delayed.

![Steps 4 and 5: questions 8 and 9](lab4_screenshot_04.png)

## 5. Inference by hand: unnormalized values and normalization

none 0.098, light 0.064, heavy 0.051, sum 0.213, P(rain = none | train = delayed) ≈ 0.4600.

![Step 5: questions 10 to 13](lab4_screenshot_05.png)

## 6. Reasoning upward: you missed the appointment

![Steps 7 and 8: questions 14 and 15](lab4_screenshot_06.png)

## 7. Two observations at once

P(maintenance = yes | delayed, heavy) ≈ 0.1176.

![Step 9: questions 17 and 18](lab4_screenshot_07.png)

## 8. Summary and submission

![Step 10: summary, exit question and submission checklist](lab4_screenshot_08.png)


[steps to solve written questions] image.png