# Watcharapon T.

AI/ML engineer. I work on computer vision and LLM systems, and I take them all the way to
something people can actually use.

On the vision side that means detection, pose estimation, OCR, face liveness, and video
pipelines that run on live camera feeds. On the language side it means retrieval, agents,
tool use, structured output, and local inference. I also build the parts around the model:
inference servers, mobile apps, dashboards, and the deployment that holds them together.

What I care about most is evaluation you can trust. A score that only exists on a
validation set is not a result, so I measure out of sample and report accuracy next to
coverage. When a model is not confident, I would rather it abstain than guess, because a
confident wrong answer costs more than no answer.

Available for freelance work. Reach me at watcharapon.thod@gmail.com.

## Selected work

**[model-proof-loop](https://github.com/watcharaponthod-code/model-proof-loop)**
A prove-then-train methodology packaged as a reusable skill. Generates free labels by
masking real data, validates with spatial-block cross-validation, and gates predictions
with conformal prediction plus a reject option. On a satellite radar to vegetation-index
gap-filling task it held 95.7% within tolerance on the cases the model chose to answer.

**[sugarcane-cv](https://github.com/watcharaponthod-code/sugarcane-cv)**
Nine detection problems solved against live industrial CCTV and audio: dust opacity,
material classification, flow estimation, and Thai license plate OCR. Includes the
training code and an evaluation that reports what actually held up on held-out days.

**[ekyc](https://github.com/watcharaponthod-code/ekyc)**
Identity verification with both passive and active liveness. Head turn, blink, and an
active flash check run against face matching. MediaPipe and DeepFace behind a FastAPI
server, wrapped as a React Native module.

**[rag-chat](https://github.com/watcharaponthod-code/rag-chat)**
Agentic retrieval platform for document search and bug tracking. LangGraph agents over
Ollama and pgvector, so inference stays local and nothing leaves the machine.

**[ninja-fruit](https://github.com/watcharaponthod-code/ninja-fruit)**
A browser game you play by moving your body in front of a webcam, using YOLOv8 pose
estimation at real-time frame rates.

**[elic](https://github.com/watcharaponthod-code/elic)**
A mobile English tutor that role-plays real situations and corrects your grammar in the
middle of the conversation. Runs on a Thai-tuned LLM with structured JSON output and
importance-scored context pruning so long sessions stay coherent.

## Stack

Python, PyTorch, OpenCV, Ultralytics, scikit-learn, LangChain, Ollama.
TypeScript, Next.js, React Native and Expo, FastAPI, PostgreSQL, Docker.

## Links

[Portfolio](https://portfolio-watcharapon.vercel.app/)
