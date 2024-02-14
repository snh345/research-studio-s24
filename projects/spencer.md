# Title

Research/Implementation of ML Sound Library for ml5.js

## Abstract

Modern machine learning has progressed to unprecedented new heights. As text-to-speech and conversational AI models have become more and more refined, advanced research has struck out to conquer some of the field’s more nebulous and complex problems. One of these problems is the field of machine learning in audio. While some of these problems are still being solved on the academic level, others have developed sophisticated models that can be used quickly and compactly, even in the browser.

Historically, machine learning models have been confined to bulky computers, and require a large amount of resources to properly function. However, recent advances in these models have made them smaller and more modular than ever before, meaning they can be hosted via Gradio, Hugging Face, or other similar hosting sites and accessed via an API on a third-party platform. This leads to some exciting new potential developments in the field of libraries for machine learning and audio on the web, especially in JavaScript.

I believe that machine learning, put into the right context, represents an opportunity for people to get into music easier than ever before, and to do more than they ever thought possible. ml5.js,  as a library for p5.js, represents the perfect space in which to implement these features. Although “newbie-friendly” audio ML libraries exist, they are not nearly as accessible as p5, and by extension, ml5. Solving this problem will help bring these powerful tools to a completely new audience.

## Objectives

This project aims to bridge the gap between accessible and fast browser-based machine learning models for audio and the novice coding community, specifically the p5.js community. Many online ML tools are quick and functional, but are ensconced in third-party websites with advanced technologies locked behind paywalls. By bringing the full capability of these tools into the p5 development ecosystem, it will be possible for creative coders to seamlessly utilize them into their multimedia projects, unlocking new creative potentials for creative code development.

Because there is a large host of tools available that could fall under the category of "audio machine learning on the web", this project hopes to lay as much groundwork and initiate as much as possible in order for a new sub-library of audio tools available via the ml5.js library to materialize. Quantitatively, this means conducting research, staging demo pages, and attempting to implement some models one at a time. The first of these tools I want to port is audio splitting; that is, taking a given sound file and separating it into 4 or 5 separate pieces which are then saved into the project. Developing this project should hopefully set the blueprint for the implementation of all future sound libraries, which can be an ongoing project. 

## References

[Sounds.Studio](https://sounds.studio/) is a very clear reference here, as it was developed by Yotam Mann, lead developer of Tone.js. Sounds.Studio has a variety of machine learning libraries to use in a DAW-based environment with capabilities far outside the scope of ml5. This website is also a good "north star" in terms of what currently is and is not doable on the web.

[Spleeter](https://github.com/deezer/spleeter) is the library that, if possible, I would like to develop a wrapper for. I've had the chance to use it before on python projects in Colab and it's pretty solid as far as I can tell. I'll continue to look for better ones to wrap (this is a good conversation to have with Yotam as well) but this is tried and true - just not easily accessible in the JavaScript environment.

[Splitter.ai](https://splitter.ai/) is the first project I encountered that performs fast audio splitting on the web. It's great, but it represents a walled garden, despite the API.

[Essentia.js](https://github.com/mtg/essentia.js/) is a great early addition to the world of browser-based ML. It suffers from two problems: it has very little appropriate documentation, and has not been updated in 3 years. Taking essentia as a "proof of concept" and extrapolating upon it in a robust and learner-friendly environment like ml5 could bring its capabilities to an entirely new demographic of learners and coders.

[Magenta.js](https://magenta.tensorflow.org/js-announce) is a fascinating and powerful ML audio library from Google that primarily uses RNN models to probabilistically develop melodies and other note sequences. This is a great piece of tech, which is actually compatible with p5.js, but it is difficult to find easy references. Furthermore, RNN generation is a highly niche problem that is adjacent to quick ML-powered tools like the ones this project hopes to implement.

I hope these references can clearly demonstrate both the viability of this technology in the ml5 space, as well as the current gap in the landscape that could be filled by merging some of these libraries into ml5.

## Methodology

Detail the methods, techniques, or approaches you will use to achieve your project objectives. Include information on any tools and technologies you plan to use. Think about how your project engages with or contributes to the community. What kinds of user testing will you do?

I'm interested in using either a wrapper or a full-on converter to port the python source code I'm interested in using (spleeter) into something usable in JavaScript. This may involve using something like [WebAssembly](https://webassembly.org/) to rebuild the spleeter library for web access, or a different similar tool. I hope to utilize a user-testing process at least once involving sitting down 5+ people and having them experiment with the prototyped UI/function calls. 

For interviews, I'll be conducting qualitative analysis based on a few questions I'm still in the process of developing. I'll turn the responses from these interviews into a handful of recommended deliverables that will be closely considered when developing the function implementation and documentation.




## Challenges

I am unfamiliar with the process of contributing to an open-source environment, and I imagine that will require some getting used to. Furthermore, I have never coded my own wrapper for a pre-existing library. In short, this entire project could be a challenge for me! I hope it can inspire me to push myself and grow.

## Final Deliverable

- Annotated bibliography
- UX Research "best practices" paper (with interviews from potential users and recommendations to consider)
- Documentation and demo page of the library/one part of the library (even if only a hi-fi Figma prototype)
- As far into a prototype/completed port of spleeter (or similar library) as I can possibly get

## Timeline

- Jan 31 - Feb 14: Conduct preliminary research and gather resources. Finalize project plan and post to class GitHub.
- Feb 14 - Feb 28: Conduct interviews and user research. Ensure that this is something people would be interested in using. Speak with experts (Yotam and/or Magdalena).
- Feb 28 - Mar 13: Finish annotated bib. Start developing wrapper in earnest. Begin drafting documentation. Continue iteratively developing prototype with user feedback.
- Mar 13 - Mar 27: More of the same. Update plan to accommodate contingencies. Finish documentation draft.
- Mar 27 - Apr 10: Finishing touches. Whatever needs to be done is finished.
- Apr 10 - Apr 17: Prepare final presentation.
