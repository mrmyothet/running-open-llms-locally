# 7. Model Licenses - Study Notes

## Main Idea

Open models are not "do anything" assets. You must follow each model's license, especially for commercial use.

## Why This Matters

Before downloading and running models locally, you should confirm legal usage conditions:

- private use
- commercial use
- attribution requirements
- prohibited use cases
- additional conditions for large-scale deployment

## Where To Check License Information

On Hugging Face model pages:

- Open the model card
- Locate the **license badge** near the top
- Follow the linked license text from the model provider

## Common License Types Mentioned

### 1. MIT / Apache 2.0 (Very Permissive)

- Usually allow commercial use
- Commonly require attribution and preservation of license notices
- Example mentioned: DeepSeek-R1 with MIT

### 2. Provider-Specific Licenses (Less Uniform)

- Examples: Meta Llama license, Google Gemma license
- Can allow commercial usage but may include extra restrictions
- May include prohibited use categories and attribution rules

## Important Example from Lesson

Meta's Llama license may include scale-related conditions (for example, very large monthly active user thresholds requiring additional permissions). Exact terms depend on the specific license version.

## Practical Compliance Checklist

Before using any open model in production:

1. Confirm the exact license version on the model card.
2. Verify private vs commercial usage rights.
3. Check attribution/notice requirements.
4. Review prohibited-use clauses.
5. Check for distribution, hosting, or scale-based restrictions.
6. Re-check terms before launch (licenses can evolve by model/version).

## Course-Relevant Takeaway

Many open model licenses are permissive, but they are still legal agreements. Always validate the terms for your specific use case.

## 1-Minute Explanation

Open LLMs are often easy to access, but usage is governed by licenses.
Some licenses like MIT/Apache are very permissive, while provider-specific licenses (like Llama or Gemma terms) may include additional obligations such as attribution, prohibited uses, or scale-related conditions.
Always read the model's license before commercial deployment.

## Memory Hook

**Open weights does not mean open usage without rules.**
