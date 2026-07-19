\# Prompt Comparison - Basic vs Improved Prompt



\## Objective



Understand how prompt quality affects the quality of AI-generated responses.



\---



\# Basic Prompt



\### Prompt



```text

Write login test cases.

```



\### Problems



\- ❌ No role defined

\- ❌ No application context

\- ❌ No functional requirements

\- ❌ No expected output format

\- ❌ No coverage specified

\- ❌ Generic AI response



\---



\# Improved Prompt



\### Prompt



```text

Act as a Senior Quality Analyst with 10+ years of experience in Web Application Testing.



Generate comprehensive test cases for the "Sign In" functionality of an e-commerce web application.



Feature Details:

\- User can sign in using a registered email address and password.

\- Email must be in a valid format.

\- Password is case-sensitive.

\- "Remember Me" checkbox is available.

\- "Forgot Password" link is available.

\- User account can be Active, Locked, or Disabled.

\- Maximum 5 failed login attempts should lock the account.

\- Successful login redirects the user to the Dashboard.



Test Coverage:

\- Positive Test Cases

\- Negative Test Cases

\- Boundary Value Analysis

\- Edge Cases

\- Validation Test Cases

\- Security Test Cases

\- UI Test Cases

\- Usability Test Cases



Output Format:

Provide the results in a Markdown table with:

\- Test Case ID

\- Test Scenario

\- Preconditions

\- Test Steps

\- Test Data

\- Expected Result

\- Priority

\- Test Type



Generate at least 40 comprehensive test cases.

```



\---



\# Comparison



| Feature | Basic Prompt | Improved Prompt |

|----------|--------------|-----------------|

| AI Role | ❌ | ✅ |

| Business Context | ❌ | ✅ |

| Functional Requirements | ❌ | ✅ |

| Test Coverage | ❌ | ✅ |

| Constraints | ❌ | ✅ |

| Output Format | ❌ | ✅ |

| Response Quality | Generic | Detailed \& Structured |



\---



\# Key Learnings



\- Better prompts produce better AI responses.

\- Clearly define the AI's role.

\- Provide business context and requirements.

\- Specify the expected output format.

\- Include constraints and coverage to guide the AI.



\---



\# Best Practices



✅ Define the AI's role.



✅ Clearly describe the task.



✅ Provide business context.



✅ Include all functional requirements.



✅ Specify test coverage.



✅ Define the desired output format.



\---



\# Prompt Formula



```

Role

\+

Task

\+

Context

\+

Requirements

\+

Constraints

\+

Output Format

```



\---



\# Conclusion



Prompt Engineering is a critical skill for AI-assisted Software Testing. Well-structured prompts generate more accurate, relevant, and reusable outputs, improving productivity and reducing the need for extensive rework.

