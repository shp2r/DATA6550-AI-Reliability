# Test Plan: Perplexity AI

## Objective
To establish a systematic testing plan for Perplexity AI's reliability, consistency and ethics through realistic scenarios that represent a user using the AI as his source of accurate and timely information.

To ensure a comprehensive evaluation, the methodologies of testing will be consistent in nature across several different types of tests so that they may be compared against one another. Thus, while Perplexity's ability to produce correct outputs will be tested, so shall be its ability to behave reliably during pressured (time constraints), ambiguous (unclear), and/or complex (multifaceted) situations. The methodologies must also yield a solid understanding of the strengths and limitations of Perplexity when delivering inaccurate or misleading outputs as results of action taken by it.

## Test Categories

### 1. Factual Accuracy Testing
This category focuses on evaluating the factual accuracy of the information provided by Perplexity AI and if it is clearly supported and adequately sourced. Since the platform uses real-time web search and citation generation, it is necessary to evaluate not only the answer given but also how closely the answer matches and accurately represents the source from which the information was obtained.

The testing will involve various types of queries such as controversial claims, commonly misunderstood facts, and questions that fall within the technical or academic range so that there is more extensive evaluation of how accurate the system was in retrieving and synthesizing the information.

Specific focus will be placed on:
- If the system provides verifiably accurate and/or information
- How accurately the system interpreted and summarized source material
- Whether the cited references substantiate the claims made
- If the sources provided are clear and relevant

By following these criteria, both the content and supporting evidence of the content will all be evaluated together rather than evaluated individually.

### 2. Consistency Testing
This evaluation's primary focus is consistency of action by the system when posed comparable or identical questions under different circumstances. User confidence should be created through consistency in the way a system performs on repeated occasions.

The testing process includes:
- You can ask the same question on several different occasions.
- You can pose the same question using varying phraseology.
- You can change the context of the conversation slightly.

The responses will be compared against one another to evaluate whether the system produces consistent results across the parameters of conclusion, reasoning and use of source materials. Any deviation from a consistent output will be evaluated to determine whether they signify substantive updates to information or an inconsistency in system behavior.

This will provide a good understanding of the level of predictability and reliability of the system's output for practical use.

### 3. Boundary Testing
This category looks at how Perplexity AI will respond when pushed to the limits of its abilities. Such tests are critical because they represent situations where users might rely on the system for important or high-risk information.

Testing includes:
- Recent or constantly changing events.
- Medical or legal questions.
- Questions that require multiple steps of reasoning or complicated decision-making.

The evaluation of the system's responses is based on:
- The system's ability to acknowledge limitations of knowledge.
- The caution displayed when operating within sensitive areas.
- Whether the system displays uncertainty at high confidence.
- The properness and reasonableness of guidance provided.

This category thus helps determine if the system will demonstrate safe operational behavior while communicating in situations requiring careful and accurate communications.

---

### 4. Edge Case Testing
This category tests the limits of the system by introducing inputs which are either unclear and/or contain logical contradictions. It is intended to help provide insight into how the system reacts to uncertain information and if it continues to generate coherent outputs when faced with complex input.

The methods of testing are:
- Providing vague or ambiguous inputs, which do not provide clear intent
- Providing prompts that have conflicting or contradictory information
- Asking questions that challenge the ethical and policy boundaries within the system

The evaluation criteria for responses are:
- How well the system is able to identify and address ambiguity
- How well the system recognizes and resolves contradiction
- Whether the system is able to maintain logical consistency throughout its response
- Whether the system produces ethical and responsible responses to all input

This category also provides insight into how well the system manages and copes with complexity and uncertainty when presented with controlled and meaningful situations.

## Documentation Plan
For all the testing to be done in an organized, consistent manner that supports effective results, every interaction that occurs during a test is documented using a specific format; this allows for clarification, transparency and repeatability for all types of tests. Each test's documentation includes:

- The exact prompt which was used
- The full response from the system was generated
- The date and time of when the interaction occurred
- The end result of the test (accurate, inconsistent, misleading, etc.)
- Supporting documentation such as screenshots or copies of saved chat logs

With this level of documentation, each and every test can be traced back to its source, reviewed, or repeated if needed. Each test's documentation also allows for a more accurate analysis of patterns developed from the results of multiple tests.

## Expected Outcomes
This assessment method creates a full profile of Perplexity AI for evaluation purposes by analyzing performance relative to several areas.  Therefore, it is anticipated that analysis will provide evidence of both positive attributes of the system as well as negative attributes.

1. System will likely be able to provide fast access to appropriate and current information.
2. Provides citations on the answers it produces.
3. Effectively answers common knowledge or simple question types from users.

The tests will also show how many areas where there was a problem with the system and/or where there will be issues due to:

1. Examples of referring to hallucinations or making unsubstantiated claims.
2. Examples that indicate some form of inconsistent responses.
3. Ethics related to providing answers when ethical boundaries are unclear.
4. Providing references that are misleading, weak, or incorrectly associated with an answer produced.

Capturing both the positive outcomes and the outcomes flagged as having issues enables this examination to provide a balanced and reasonable assessment of performance.  Therefore, the information gathered here will provide significant evidence to prove or disprove the expected performance of the system.   This examination will also include an analysis of the situations where reliability is critical to obtaining the anticipated outcomes, and where the expected outcome will not occur.
