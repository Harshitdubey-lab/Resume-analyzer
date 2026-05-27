# Resume-analyzer
# Production-Grade AI Resume Analyzer

A high-performance, intelligent career intelligence system with semantic matching and role-based analytics.

## Advanced Features
- **Semantic JD Matching**: Uses vector-based similarity to match resumes with job descriptions.
- **Role Intelligence**: Custom scoring benchmarks for Software Engineers, Data Scientists, and Web Developers.
- **Keyword Analytics**: Detailed density analysis, gap detection, and overused keyword flags.
- **Improvement Engine**: Logic-based bullet point rewriter to transform weak achievements.
- **Formatting Auditor**: Automatically detects length issues, structural inconsistencies, and readability gaps.
- **Midnight Pro UI**: A premium, high-contrast glassmorphic dashboard with animated analytics.

## Technical Upgrades
- **Backend**: FastAPI with `AdvancedAnalyzer` class for modular processing.
- **NLP**: Enhanced `spaCy` pipelines and `TfidfVectorizer` with N-gram support.
- **Frontend**: Custom CSS variable system for the Midnight Pro theme and Chart.js integration for visual scoring.

## Setup
1. `pip install -r requirements.txt`
2. `python -m spacy download en_core_web_sm`
3. `python -m uvicorn backend.main:app --reload`

## Project Structure
- `backend/role_data.py`: Centralized job role skill database.
- `backend/model.py`: Advanced analysis engine.
- `frontend/`: Premium UI assets.
