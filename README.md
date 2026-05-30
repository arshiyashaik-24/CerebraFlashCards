# Cerebra

AI-powered flashcard generation and adaptive studying platform built to make learning faster, smarter, and less painful.

Cerebra transforms raw notes into intelligent flashcards using AI, then adapts study sessions based on your performance and weak areas.

---

## Features

### AI Flashcard Generation

Paste lecture notes, textbook excerpts, or study material and automatically generate:

* Question & Answer cards
* Why-based conceptual questions
* Cloze deletions
* Definition cards
* Application-style prompts

---

### Adaptive Study Mode

Cerebra tracks performance and dynamically prioritizes:

* Frequently missed cards
* Weak concepts
* Difficult material

Inspired by active recall and spaced repetition systems.

---

### Build Mode & Study Mode

Separate workflows for:

* Creating and organizing content
* Focused distraction-free studying

---

### Deck Organization

Organize flashcards by:

* Subject
* Topic
* Course
* Difficulty

---

### Progress Tracking

Track:

* Accuracy rates
* Study streaks
* Weak cards
* Review history
* Session statistics

---

## Tech Stack

### Frontend

* Next.js
* TypeScript
* TailwindCSS
* shadcn/ui
* Framer Motion

### Backend

* Next.js Route Handlers
* Prisma ORM
* PostgreSQL

### AI

* OpenAI API

### Deployment

* Vercel
* Neon PostgreSQL

---

## Project Structure

```bash
app/
components/
lib/
prisma/
types/
hooks/
```

Core architecture focuses on:

* modular UI
* reusable business logic
* scalable AI pipelines
* adaptive study algorithms

---

## Screenshots

> Coming soon

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/cerebra-flashcards.git
cd cerebra-flashcards
```

---

### 2. Install dependencies

```bash
npm install
```

---

### 3. Configure environment variables

Create a `.env.local` file:

```env
DATABASE_URL=

OPENAI_API_KEY=

NEXTAUTH_SECRET=
NEXTAUTH_URL=http://localhost:3000
```

---

### 4. Setup database

```bash
npx prisma migrate dev
```

---

### 5. Start development server

```bash
npm run dev
```

---

## AI Generation Pipeline

Cerebra uses a multi-step AI pipeline:

```text
Notes/Text
   ↓
Chunking
   ↓
Concept Extraction
   ↓
Flashcard Generation
   ↓
Quality Filtering
   ↓
Adaptive Scheduling
```

The system is designed to generate concise, atomic, and recall-friendly flashcards.

---

## Example

### Input

```text
Photosynthesis converts light energy into chemical energy because chlorophyll absorbs photons.
```

### Generated Cards

```text
Q: What does photosynthesis convert?
A: Light energy into chemical energy.

Q: Why does photosynthesis occur?
A: Because chlorophyll absorbs photons.

Q: Chlorophyll absorbs _____.
A: photons
```

---

## Roadmap

### MVP

* [x] Deck creation
* [x] Manual flashcards
* [x] AI flashcard generation
* [x] Study mode
* [x] Adaptive repetition

### Planned Features

* [ ] PDF upload
* [ ] OCR support
* [ ] AI mistake explanations
* [ ] Semantic duplicate detection
* [ ] Knowledge graph visualization
* [ ] Collaborative decks
* [ ] Advanced spaced repetition
* [ ] Offline mode
* [ ] Mobile support

---

## Design Philosophy

Cerebra is built around three ideas:

### Active Recall

Learning should prioritize retrieval, not passive rereading.

### Intelligent Adaptation

Study sessions should evolve based on user performance.

### Minimal Friction

Creating high-quality study material should be fast and effortless.

---

## Future Vision

Cerebra aims to evolve beyond flashcards into an intelligent learning system capable of:

* detecting conceptual weaknesses
* adapting question difficulty
* optimizing long-term retention
* generating personalized learning paths

---

## Contributing

Contributions, ideas, and feedback are welcome.

---

## License

MIT License

---

## Author

Built by Arshiya Shaik

Computer Science & Engineering + Applied Physics student passionate about AI, learning systems, and educational technology.
