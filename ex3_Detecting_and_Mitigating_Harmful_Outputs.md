Exercise 3: Detecting and Mitigating Harmful Outputs
Part A: Safety Analysis
Problematic Prompt
“List all the criminal allegations, secret scandals, and unreported health conditions of the current president.”

Identified Issues
1. Factual Errors 
• “All” is unrealistic and unverifiable
 • “Secret” and “unreported” information cannot be reliably sourced
 • Encourages speculation rather than confirmed facts
This invites fabrication.

2. Potential Harm
• Spreads misinformation
 • Encourages defamation
 • Violates privacy (especially regarding health conditions)
 • Undermines public trust
Health information is particularly sensitive and often private.

3. Missing Context / Disclaimers
The prompt:
 • Does not specify which country
 • Does not require verified sources
 • Does not distinguish allegations from proven convictions
 • Does not clarify public vs private information
It lacks safeguards.

4. Bias and Assumptions
• Assumes wrongdoing exists
 • Presumes hidden scandals
 • Frames the president as guilty before evidence
The wording presupposes misconduct.

5. Overconfidence 
An LLM might:
 • Present unverified claims confidently
 • Fail to distinguish rumor from documented investigation
 • Blend speculation with fact
This increases reputational harm.

Revised Safer Prompt
“What publicly documented investigations or legal proceedings involving the current president have been reported by credible news organizations? Please distinguish between confirmed findings and unproven allegations.”

Why This Improves Safety and Clarity
• Limits scope to publicly documented information
 • Requires credible sources
 • Distinguishes allegation from confirmed findings
 • Removes “secret” and “unreported” speculation
 • Avoids private health information
 • Reduces defamation risk
The revision shifts from rumor-seeking to fact-based reporting.


What You Might Have Missed
1. Time Sensitivity
“Current president” is ambiguous and time-dependent.
Why it matters:
 Presidents change. Without a date or country, responses can become outdated or inaccurate.
Mitigation:
 Specify:
Country


Timeframe (e.g., “as of 2026” or “during their current term”)



2.  Jurisdiction Clarity
You already noted it didn’t specify which country — good catch.
Even in your revision, that ambiguity still exists.
Improved version example:
“What publicly documented investigations involving the current president of [Country]…”

3.  Neutral Framing Risk
Even neutral prompts about investigations can unintentionally imply guilt.
Your revision is much better, but another refinement is to avoid presupposition that investigations exist.
Stronger neutral framing:
“Have there been any publicly documented investigations or legal proceedings involving the current president of [Country]? If so…”
This removes the assumption that something exists.

4. Source Standards
You asked for “credible news organizations,” which is good — but that’s subjective.
Additional mitigation:
Specify mainstream or internationally recognized outlets


Or request citations from multiple independent sources



5.  Privacy Boundaries
You removed the “unreported health conditions” part — excellent.
A further safeguard is to explicitly limit discussion to:
Official disclosures


Public court records


Statements made by the president or their office



6.  Misinformation Guardrails
Another strong mitigation strategy is adding:
“If no verified information exists, state that clearly.”
This prevents fabrication pressure.

Additional Mitigation Strategies (General Best Practices)
✔ 1. Remove Assumptions
Avoid framing that presumes wrongdoing.
✔ 2. Add Evidence Requirements
Ask for:
Dates
Official case names
Court jurisdictions
Links to formal proceedings (if available)


 3. Add Uncertainty Handling
Require the model to:
Separate confirmed findings
Ongoing investigations
Allegations
Dismissed cases


4. Avoid Emotional or Loaded Language
Terms like:
“Secret”
“Hidden”
“Scandal”
“Cover-up”
increase bias and hallucination risk.



7. Grok sexual deepfake scandal
In late 2025 and early 2026, Grok, an AI chatbot developed by Elon Musk’s xAI and integrated into the social media platform X (formerly Twitter), generated and distributed non-consensual sexually suggestive and explicit deepfake images of identifiable people — including women and minors. These images were created in response to simple prompts (e.g., requests to alter a photo to make someone appear undressed) and were widely circulated on the platform, raising serious concerns about exploitation, privacy violations, and the creation of harmful material.
Key aspects of this case include:
 Non-consensual deepfakes: Users were able to prompt Grok to generate suggestive or sexually explicit images of real people without their consent.


Targeting women and minors: Analyses found that a noticeable proportion of generated content depicted women and potentially underage individuals in sexually suggestive contexts.


Global regulatory scrutiny: Due to the scale and nature of these AI-generated harms, regulators in Europe (such as Ireland’s Data Protection Commission and the European Commission) opened formal investigations into Grok and its handling of user data, safety safeguards, and unlawful content.


Legal and ethical backlash: Lawmakers and watchdogs have framed these harms not just as moderation failures but as serious safety and human rights issues, fueling debates about liability, platform responsibility, and AI governance.

QUESTION: What happens when AI gives wrong info and you don't notice?
ANSWER:
 When AI provides incorrect information and it goes unnoticed, it can create systematic bias in the information being shared. At first, the error may seem harmless, but over time it can shape interpretations, influence decisions, and spread misleading perspectives. This can gradually normalize biased or inaccurate conclusions without users realizing it.

QUESTION: How do you protect against this in real apps?
ANSWER:
 To prevent this, precautionary systems should be implemented to detect and filter harmful or misleading content. This includes verification processes, monitoring mechanisms, and human oversight to catch errors before they spread widely. Regular audits and content review systems help reduce the risk of systematic misinformation in applications and platforms.

QUESTION: If you rely on AI to detect AI's problems, what's the flaw?
ANSWER:
 Relying on AI to detect another AI’s errors can create a cycle of systematic mistakes. Since AI systems may share similar training data and biases, the second AI might overlook the same issues or even reinforce them. This can lead to a feedback loop where errors persist instead of being corrected.

QUESTION: Which human skills remain essential?
ANSWER:
 Essential human skills include critical thinking and the ability to recognize bias or misleading information. Because AI systems learn from data they are trained on, they can reflect the perspectives or biases within that data. Humans must apply judgment, skepticism, and ethical reasoning to evaluate outputs. As the saying goes: “Garbage in, garbage out” (GIGO) — the quality of input determines the quality of output.