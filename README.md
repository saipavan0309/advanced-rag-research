# Advanced RAG Research

**Comprehensive research toolkit combining domain-optimized RAG systems with extensive LLM evaluation frameworks.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

This repository provides two integrated research components for advanced retrieval-augmented generation and language model evaluation, designed for researchers and practitioners working with modern AI systems.

## Overview

### RAG System with Domain Optimization
- **Multi-domain RAG implementation** across 5 specialized domains
- **Advanced retrieval pipeline** with BGE embeddings and cross-encoder reranking
- **RAGBench evaluation** with comprehensive metrics
- **Production-ready architecture** with optimized chunking strategies

### RGB LLM Evaluation Suite
- **Information Integration Testing** - Multi-component question answering
- **Factual Accuracy Evaluation** - Document-based verification
- **Noise Robustness Analysis** - Performance under varying noise levels
- **Negative Rejection Testing** - Ability to refuse unanswerable questions

## Key Features

**RAG System:**
- Domain-specific optimization for Biomedical Research, Legal, Customer Support, General Knowledge, and Finance
- Advanced embedding models (BGE-Large, MiniLM) with domain-specific selection
- Cross-encoder reranking for improved retrieval accuracy
- Interactive Gradio interface for real-time testing
- Comprehensive evaluation against RAGBench metrics

**LLM Evaluation:**
- Support for 5+ models including LLaMA, Qwen, Gemma, DeepSeek
- Automated result analysis with CSV exports
- Reproducible methodology following RGB research standards
- Configurable sample sizes and noise ratios

## Quick Start

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
8GB+ RAM (recommended)
GROQ API access
