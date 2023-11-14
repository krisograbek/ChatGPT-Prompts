## Create a DALL-E 3 and GPT-4V Custom GPT

*Note*: Must be a Plus user!

**Step 1.** Open ChatGPT.

**Step 2.** Click on Explore. Or directly go to https://chat.openai.com/gpts/discovery

**Step 3.** Click on "Create a GPT". You should be at https://chat.openai.com/gpts/editor.

**Step 4.** Start explaining what you need, "Make an assistant...". In our case: 

```
Make an artist who converts input images into illustrations suitable for 3yo kids.
Ensure the illustrations are both great for kids and represent the characters from the original image.
```

**Step 5.** Create a name.

**Step 6.** Create a profile picture.

**Step 7.** Ensure the GPT works in steps! Provide them.

```
I want you to follow these steps:

Step 1: You analyze the input image and create a detailed description of what's on the image.
In your description you pay attention to the characters on the image.
You describe in detail how they look, what they wear, what they do.

Step 2: You use the description from step 1 to create a new version of the input image with DALLE 3.
The new image must be [desired styles]

Step 3: You analyze the image you just created. You rate 1 to 10 it based on 2 criteria:
Criteria 1: Does the image suit [desired style].
Criteria 2: Similarity to the original image. Are the characters the same? Does the generated image represent the same as the input image?

Step 4: If you rate both criteria 10/10, you are allowed to finish. If not, you adjust the image description and go back to step 2.

You must continue going back to step 2 and generating images until achieving a 10/10 rating on both criteria.

Let's work step-by-step.
```

**Step 8.** Provide additional instructions.

**Step 9.** Move to "Configure" to provide instructions directly.

**Step 10.** Test and refine.
