{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "f6bc01f6-b8a2-475e-9ecb-3fb97189c475",
   "metadata": {},
   "source": [
    "# Ethics Reflection\n",
    "## Week 2 Day 3 · Kevin Kirui · 20 March 2026\n",
    "\n",
    "---\n",
    "\n",
    "## What makes AI deployment in healthcare different from other domains?\n",
    "\n",
    "Unlike a spam filter, a medical AI model trained on one hospital's data may encounter\n",
    "a completely different patient population, disease prevalence, and imaging equipment\n",
    "at the next deployment site, and fail silently. CheXNet is a good example: it was\n",
    "trained on ChestX-ray14, a frontal-view dataset from a single US hospital system,\n",
    "with labels derived from NLP on radiology reports rather than direct image annotation.\n",
    "A model that learns from noisy, single-site labels can look strong on internal\n",
    "benchmarks yet behave very differently on X-rays from a Kenyan public hospital, which\n",
    "makes the data problem in healthcare fundamentally about safety and equity, not just\n",
    "generalisation error.\n",
    "\n",
    "CheXNet also demonstrates the validation problem. The paper reports strong AUC and F1\n",
    "scores and shows that the ROC curve sits above individual radiologist operating points\n",
    "— but the threshold used for that comparison was selected after seeing the test set,\n",
    "which flatters the model in a way that would not hold in prospective deployment. More\n",
    "fundamentally, the paper shows nothing about whether using the model improves patient\n",
    "outcomes, reduces missed pneumonias, or avoids workflow disruptions in real wards. In\n",
    "a movie recommendation system, better AUC on a test set is usually enough to ship; in\n",
    "a diagnostic tool, benchmark performance without prospective, multi-site clinical\n",
    "validation is not.\n",
    "\n",
    "These two problems — unreliable data and unvalidated outcomes — converge in a third:\n",
    "accountability. When a streaming service recommends the wrong film, no one is harmed.\n",
    "When a clinical AI flags a pneumonia case as normal and a clinician trusts it, the\n",
    "harm is borne by the patient while responsibility is blurred between the clinician,\n",
    "the hospital, the vendor, and the regulator. Existing medical liability frameworks\n",
    "assume human decision-makers, not opaque software deployed in environments it was\n",
    "never tested in, so questions of consent, auditability, and shared responsibility\n",
    "remain unsettled. To help close these gaps, I need to go beyond model building into\n",
    "clinical validation design, regulatory science for SaMD, and practical human-AI\n",
    "interaction design — which is exactly the space the Stanmore programme is pushing me\n",
    "to think about.\n",
    "\n",
    "---\n",
    "\n",
    "### Key sources\n",
    "- Rajpurkar et al. (2017). *CheXNet: Radiologist-Level Pneumonia Detection on Chest\n",
    "  X-Rays with Deep Learning.* arXiv:1711.05225\n",
    "- Google PAIR. *People + AI Guidebook*, Chapters 1 and 3."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "190c5977-06d2-4110-82ad-ba38d1369e2f",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.15"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
