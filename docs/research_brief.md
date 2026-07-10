# Research Brief

## Project Name

ShiftLens Vision Bench: Computer vision for Johnson-Aligned Research

## Motivation

This project targets **Computer vision, vision+language, image generation, 3D** with a concrete, reproducible artifact rather than a vague expression of interest. The goal is to show research taste, useful engineering, and honesty about what has and has not been completed.

## Hypothesis

A focused system that combines domain-specific task design with rigorous baselines and failure analysis can produce a useful lab contribution even before a full publication-scale result exists.

## Proposed Value

Build **a robustness and failure-analysis benchmark for vision or vision-language models** focused on **Computer vision**.

## Data Plan

Build a small curated evaluation suite over 3-5 distribution shifts and compare CLIP/ViT-style baselines against adaptation or calibration variants.

## Baselines And Comparisons

Use the strongest simple baseline first, then add the proposed contribution only after the baseline is reproducible. The expected comparisons should include standard baselines, one stronger modern baseline, the proposed method or evaluation contribution, and an ablation with the key contribution removed.

## Evaluation Metrics

Use metrics appropriate to the area plus reproducibility checks: performance, calibration or uncertainty when relevant, failure slices, runtime/cost, and limitations.

## Failure Analysis

Maintain a failure bank with input, expected behavior, observed behavior, suspected cause, remediation attempt, and whether the fix generalized.

## Outreach Claim You Can Safely Make

You can say you have prepared a project scaffold and are ready to turn it into a reproducible contribution. Do not claim completed experiments until they exist.
