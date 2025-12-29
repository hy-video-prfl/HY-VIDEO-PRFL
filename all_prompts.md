<style>
table th:first-of-type {
    width: 5%;
}
table th:nth-of-type(2) {
    width: 45%;
}
table th:nth-of-type(3) {
    width: 25%;
}
table th:nth-of-type(4) {
    width: 25%;
}
</style>

# Video Generation Models are Good Latent Reward Models

In this document, we display full frames of result videos mentioned in our paper and more visual results of our method of different settings.

## Visual results mentioned in our paper

### Visual results of our method
Full frames of result videos in Figure 1. The resolution of all videos in Figure 1 is 720P.

|Task|Prompt|Image|Video|
| --- | --- | --- | --- |
|T2V|A woman with short gray hair wearing glasses and headphones plays a small keyboard.|-|<video src="assets/teaser/eb6b2f8ae73a0ce016f6b199413e4cea_seed_708785.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|T2V|Four people hold sparklers by a body of water at sunset.|-|<video src="assets/teaser/artlist_video_b4fb6983929b65fb19456d7de59e4df6_seed_109649.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|I2V|a man standing on top of a sand dune in the desert|![](assets/teaser/135_seed_740089.jpg)|<video src="assets/teaser/135_seed_740089.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|I2V|A Caucasian woman with short, curly pink hair wearing a pink striped robe over pink athletic wear dances in a kitchen. She is wearing headphones and holding a smartphone connected by a white cable. The kitchen has white cabinets, a wooden countertop, and white tile backsplash. There are apples on the counter near an electric kettle.|![](assets/teaser/a5e2ab6f87226b5fb169d3d854eb1c4d_seed_223210.jpg)|<video src="assets/teaser/a5e2ab6f87226b5fb169d3d854eb1c4d_seed_223210.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|

### Comparison with other methods
Full frames of result videos in Figure 6. The task and resolution of all videos in Figure 6 is T2V and 480P.

|Method|Case1|Case 2|
| --- | --- | --- |
|Prompt|A woman in a flowing white dress is dancing gracefully in a modern dance studio. Her movements are fluid and expressive, with arms sweeping widely and legs moving in elegant, rhythmic patterns. She has long wavy hair that flows freely with each movement, catching the soft lighting from above. The background is a minimalist setup with black walls and a few abstract paintings hanging on them. The camera follows her from a medium shot, capturing her full body as she dances, then moves to a close-up of her face, highlighting her joyful expression and the sparkle in her eyes. The video has smooth transitions and dynamic camera movements, including tracking shots and slow-motion sequences to emphasize her graceful movements.|Four people are seated on an ornate rug in a room with exposed brick walls. One man holds an acoustic guitar. Instruments including a saxophone and harmonica rest on the floor near them. The individuals have varying hair colors and styles; one woman has long dreadlocks. They wear casual clothing like t-shirts, jeans, and sneakers.|
|Pretrain|<video src="assets/comp/10_seed_227898.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|<video src="assets/comp/19fe336a66c4ab9006a7f141975a30e3_seed_890287.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|SFT|<video src="assets/comp/10_seed_227898_1.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|<video src="assets/comp/19fe336a66c4ab9006a7f141975a30e3_seed_890287_1.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|RWR|<video src="assets/comp/10_seed_227898_2.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|<video src="assets/comp/19fe336a66c4ab9006a7f141975a30e3_seed_890287_2.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|RGB ReFL|<video src="assets/comp/10_seed_227898_3.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|<video src="assets/comp/19fe336a66c4ab9006a7f141975a30e3_seed_890287_3.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|PRFL|<video src="assets/comp/10_seed_227898_4.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|<video src="assets/comp/19fe336a66c4ab9006a7f141975a30e3_seed_890287_4.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|


## More visual results of our method

|Task & Resolution|Prompt|Image|Video|
| --- | --- | --- | --- |
|T2V 480P|Two shirtless men with short dark hair are sparring in a dimly lit room. They are both wearing boxing gloves, one red and one black. One man is wearing white shorts while the other is wearing black shorts. There are several screens on the wall displaying images of buildings and people.|-|<video src="assets/more/85216a8012f4e8bf85fb219bc8453774_seed_579180.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>
|T2V 480P|The woman has dark eyes and is holding a black smartphone to her ear with her right hand. She is typing on the keyboard of an open silver laptop computer with her left hand. Her fingers have blue nail polish. She is sitting in front of a window covered by sheer white curtains.|-|<video src="assets/more/490d22e34d0fdf1aba9e1ba9e20d667d_seed_218637.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|T2V 720P|A woman with fair skin, dark hair tied back, and wearing a light green t-shirt is visible against a gray background. She uses both hands to apply a white substance from below her eyes upward onto her face. Her mouth is slightly open as she spreads the cream.|-|<video src="assets/more/e2e6dff4025869caa55f4baaa8cd5208_seed_634237.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|T2V 720P|A light-skinned man with short hair wearing a yellow baseball cap, plaid shirt, and blue overalls stands in a field of sunflowers. He holds a cut sunflower head in his left hand and touches it with his right index finger. Several other sunflowers are visible in the background, some facing away from the camera.|-|<video src="assets/more/76dfec95b2b525b10014e6e43612f1d0_seed_588308.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|I2V 480P|a monochromatic video capturing a cat's gaze into the camera|![](assets/more/14_seed_876367.jpg)|<video src="assets/more/14_seed_876367.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|I2V 480P|A family of four eats fast food at a table.|![](assets/more/artlist_video_60ca5873a5c21ff4e4785b1997239d87_seed_561368.jpg)|<video src="assets/more/artlist_video_60ca5873a5c21ff4e4785b1997239d87_seed_561368.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|I2V 720P|a young boy is jumping in the mud|![](assets/more/109_seed_677347.jpg)|<video src="assets/more/109_seed_677347.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|
|I2V 720P|Normal speed, Medium shot shot, Eye level angle, Third person viewpoint, Static camera movement, Frame-within-frame composition, Shallow depth of field, Natural light light, Cinematic style, Desaturated palette with slate blue, dusty rose, and dark wood tones color palette, Dramatic atmosphere, The scene is set on a patio or veranda, framed by a stone archway. In the back, there is a large, weathered wooden gate set into a stone wall. background,  IP. In a static outdoor shot, six people are gathered on a stone patio in front of a large wooden gate. On the right, two men are seated at a dark wooden table. An older man in a grey traditional jacket holds a cane and gestures with his right hand while speaking. A younger man in a light grey suit sits beside him, listening. On the left side of the frame, a man in a dark suit stands with his back to the camera. Next to him, a woman in a pink patterned cheongsam and a woman in a grey skirt suit are standing close together, whispering. The women then turn and smile towards the men at the table. The man in the dark suit turns to face the group, revealing a newborn baby cradled in his arms, wrapped in a pink blanket. He takes a few steps forward, holding the baby. The women look at him and the infant. The older man at the table continues to talk, now gesturing towards the man with the baby. The man holding the baby looks down at the infant as he continues to walk slowly. The table is set with white cups, plates, fruit, and a dark wooden box.|![](assets/more/real_1246_seed_277973.jpg)|<video src="assets/more/real_1246_seed_277973.mp4" controls="controls" width="300" autoplay="autoplay" loop="loop"></video>|