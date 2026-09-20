<h1 align="center">Watcharapon Thodraksa</h1>

<p align="center">
  <b>AI / ML Engineer</b> · Computer Vision &amp; LLM Systems<br/>
  <sub>Bangkok, Thailand · Available for freelance work</sub>
</p>

<p align="center">
  <a href="https://portfolio-watcharapon.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:watcharapon.thod@gmail.com"><img src="https://img.shields.io/badge/Email-1A1A1A?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/watcharaponthod-code?tab=followers"><img src="https://img.shields.io/github/followers/watcharaponthod-code?style=flat-square&color=1A1A1A&labelColor=1A1A1A" alt="Followers"/></a>
</p>

---

I work on computer vision and LLM systems, and I take them all the way to something people
can actually use.

On the vision side that means detection, pose estimation, OCR, face liveness, and video
pipelines that run on live camera feeds. On the language side it means retrieval, agents,
tool use, structured output, and local inference. I also build the parts around the model:
inference servers, mobile apps, dashboards, and the deployment that holds them together.

What I care about most is evaluation you can trust. A score that only exists on a validation
set is not a result, so I measure out of sample and report accuracy next to coverage. When a
model is not confident, I would rather it abstain than guess: a confident wrong answer costs
more than no answer.

<br/>

### Selected work

<table>
<tr>
<td width="50%" valign="top">

#### [model-proof-loop](https://github.com/watcharaponthod-code/model-proof-loop)

A prove-then-train methodology packaged as a reusable skill. Generates free labels by masking
real data, validates with spatial-block cross-validation, and gates predictions with conformal
prediction plus a reject option.

On a satellite-radar to vegetation-index gap-filling task it held **95.7% within tolerance**
on the cases the model chose to answer.

<sub>`Python` · `LightGBM` · `conformal prediction`</sub>

</td>
<td width="50%" valign="top">

#### [sugarcane-cv](https://github.com/watcharaponthod-code/sugarcane-cv)

Nine detection problems solved against live industrial CCTV and audio: dust opacity, material
classification, flow estimation, and Thai licence-plate OCR.

Includes the training code and an evaluation that reports what actually held up on held-out
days.

<sub>`PyTorch` · `Ultralytics` · `OpenCV`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [ekyc](https://github.com/watcharaponthod-code/ekyc)

Identity verification with both passive and active liveness. Head turn, blink and an
active-flash check run against face matching.

MediaPipe and DeepFace behind a FastAPI server, wrapped as a React Native module.

<sub>`MediaPipe` · `DeepFace` · `FastAPI` · `React Native`</sub>

</td>
<td width="50%" valign="top">

#### [rag-chat](https://github.com/watcharaponthod-code/rag-chat)

Agentic retrieval platform for document search and bug tracking. LangGraph agents over Ollama
and pgvector, so inference stays local and nothing leaves the machine.

<sub>`LangGraph` · `Ollama` · `pgvector`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [ninja-fruit](https://github.com/watcharaponthod-code/ninja-fruit)

A browser game you play by moving your body in front of a webcam, using YOLOv8 pose estimation
at real-time frame rates.

<sub>`YOLOv8-pose` · `OpenCV` · `Python`</sub>

</td>
<td width="50%" valign="top">

#### [elic](https://github.com/watcharaponthod-code/elic)

A mobile English tutor that role-plays real situations and corrects your grammar mid-conversation.
Runs on a Thai-tuned LLM with structured JSON output and importance-scored context pruning, so
long sessions stay coherent.

<sub>`React Native` · `Expo` · `Typhoon ThaiLLM` · `Gemini`</sub>

</td>
</tr>
</table>

<br/>

### Stack

<table>
<tr>
<td><b>Machine learning</b></td>
<td>Python · PyTorch · OpenCV · Ultralytics · scikit-learn · LangChain · Ollama</td>
</tr>
<tr>
<td><b>Application</b></td>
<td>TypeScript · Next.js · React Native &amp; Expo · FastAPI</td>
</tr>
<tr>
<td><b>Infrastructure</b></td>
<td>PostgreSQL · Docker · MLflow</td>
</tr>
</table>

<br/>

<p align="center">
  <sub><a href="https://portfolio-watcharapon.vercel.app/">Portfolio</a> · <a href="mailto:watcharapon.thod@gmail.com">watcharapon.thod@gmail.com</a></sub>
</p>
