Name | Jordan Lambino
Email | jlambino@ucsd.edu


Section | B15
Mentor | Yu-Xiang Wang

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic I've covered in my domain this quarter was removing invisible watermarks from images. Although this topic is somewhat separate from differential privacy, it helped to understand certain methods of attacking AI watermarks. Reading about this topic offered an alternative perspective to privacy, particularly using simliar mechanisms (Gaussian mechanism) and generative AI for watermark removal.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

For my Quarter 2 Project, one potential investigation I would like to pursue is to incorporate an augmented Private Evolution (PE) algorithm for Intel telemetry data. As of now, the approach through which we attempt to guarantee Differential Privacy (DP) is open ended. Since the structure of Intel telemetry data may not be as straight-forward as images or text, I'm interested in analyzing how we can tweak previous DP approaches for our purposes. This augmented PE algorithm would likely include a Gaussian mechanism, used in conjunction with an LLM to generate synthetic data. Though we don't exactly know how the telemetry data is structured, this hypothetical investigation would likely involve altering the PE algorithm for additional preprocessing steps. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

Our current Quarter 1 Project attempts to perform standard noise addition and alternative synthetic data generation techniques on clinical data. As of now, we are only evaluating DP techniques on medical data; one potential change I would make to our approach is adding another dataset to the investigation. Doing so would not only add validity to our approaches, but also demonstrate how the proposed methods perform on different datasets. This could lead to intriguing conclusions and would provide helpful context as we eventually apply DP methods to Intel telemetry data.

**What other techniques would you be interested in using in your project?**

One technique I would be interested in using is somehow incorporating an Exponential mechanism on top of a Gaussian mechanism to guarantee DP. Most of the DP techinques we've studied exclusively leverage either the Exponential or Gaussian mechanism; it might be interesting to combine both to provide additional randomness to the synthetic data generation. An additional technique I would want to explore is evaluating DP algorithms on multiple values of the privacy budget. Combined with the proposed changes above, this technique would allow our group to analyze how DP methods react to different privacy budgets.

