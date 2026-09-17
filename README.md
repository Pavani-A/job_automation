Bangalore Development Job Automation

An AI-powered job-search automation focused specifically on Bangalore/Bengaluru development roles for candidates with 0–1 year of experience.

The automation searches relevant job platforms and company career pages, filters out unsuitable roles, selects the most appropriate resume for each job, and prepares tailored application materials.

🎯 Search Criteria

The following are hard filters:

Location: Bangalore / Bengaluru only

Relevant experience: 1 year of Software Engineering internship experience

Experience eligibility: The job's stated experience range must include 1 year, or explicitly accept freshers/entry-level candidates

Role type: Development / Software Engineering only

Location: Bangalore / Bengaluru only

Application threshold: Materials are prepared only for roles with a Fitness Score of 70% or higher after the hard filters pass

Experience Eligibility

Because the candidate has 1 year of Software Engineering internship experience, the automation evaluates the stated experience range rather than searching only for an exact 0–1 years label.

Job requirement

Eligible?

Fresher / Graduate / Entry Level

✅

0–1 years

✅

0–2 years

✅

0–3 years

✅

1 year

✅

1–2 years

✅

1–3 years

✅

1–4 years

✅ when appropriate for an entry-level/junior role

2–3 years

❌

2+ years

❌

3+ years

❌

Rule: Accept when the candidate's 1 year falls within the stated range. Reject when the minimum required experience is greater than 1 year.

Target Roles

Examples include:

Software Engineer / Software Developer

SDE / SDE-1

Backend Developer / Backend Engineer

Python Developer / Python Backend Developer

Full Stack Developer

Java Backend Developer

AI/ML/GenAI Engineer when the role is genuinely development-focused

Excluded Roles

The automation excludes roles such as:

QA / Quality Analyst

Manual Testing

Test Engineer

Automation Testing

SDET

Technical Support

Production Support

IT Support

Customer Support

Operations

Non-development analyst roles

Roles whose minimum required experience is greater than 1 year

Roles outside Bangalore/Bengaluru

📄 Intelligent Resume Selection

The automation does not blindly use one resume for every application.

It first identifies the primary responsibilities and technology stack in the job description and selects the most relevant base resume:

Job focus

Base resume

Python, FastAPI, Django, Flask, REST APIs, backend

Pavani_python.pdf

React/Next.js + backend/full-stack

Pavani_full_stack.pdf

AI/ML/GenAI development

Pavani_AI.pdf

Java, Spring Boot, backend services

Pavani_full_stack.pdf

General software development / SDE

Pavani_A.pdf

The selected resume is then tailored to the specific job description.

The automation never invents skills, experience, achievements, or technologies that are not supported by the user's actual background.

🔎 Job Search

The automation can search relevant Indian job platforms and company career pages.

For each potential job it:

Checks the Bangalore location requirement.

Checks the 0–1 year experience requirement.

Checks that the role is development-focused.

Removes duplicates.

Verifies the job link where possible.

Scores the candidate's fit against the job.

Selects the appropriate base resume.

Tailors the resume to the job.

Creates a tailored cover letter.

Provides the direct application link.

Jobs that fail a hard filter are not included in the main results.

📦 Application Materials

For qualifying jobs, the automation prepares:

A job-specific ATS-friendly resume

A job-specific cover letter

Direct application link

Match/fitness explanation

Materials can be bundled by company for easier review.

The user reviews the materials and submits applications manually.

🤖 Automation

The /job-skill automate command can be used to configure a recurring job search.

A scheduled run:

Searches for newly posted qualifying jobs.

Applies the Bangalore + 0–1 year + development-only filters.

Deduplicates results.

Scores eligible jobs.

Selects the correct resume for each job.

Generates tailored resumes and cover letters for qualifying matches.

Updates the application tracker.

Produces a report with the matching jobs and application materials.

🧰 Commands

/job-skill help

Displays the available commands and usage information.

/job-skill search

Runs a job search using the configured Bangalore development criteria.

/job-skill automate

Sets up a recurring job-search schedule.

/job-skill status

Checks and tracks application statuses when the required email/application tracking integration is available.

📊 Application Tracking

The automation can maintain a job_tracker.xlsx containing information such as:

Date Found

Company

Role

Job ID

Platform

Location

Posted Date

Job URL

Fitness Score

Resume Generated

Cover Letter

Application Status

Date Applied

Response Date

Interview Stage

Notes

Next Action

✍️ Resume & Cover Letter Principles

Application materials should:

Read naturally and professionally.

Reflect the user's actual experience.

Use relevant terminology from the job description.

Avoid unnecessary AI-style language and clichés.

Never fabricate experience or skills.

Keep the resume ATS-friendly.

Focus on the most relevant projects, skills, and experience for each role.

🚫 What It Does Not Do

The automation does not:

Automatically submit applications.

Bypass CAPTCHAs, OTPs, or login requirements.

Create accounts on job portals.

Invent qualifications to make a candidate appear eligible.

The final application decision and submission remain with the user.

📁 Main Automation File

job-skill-bangalore-development-0-1y.md

This is the Claude automation definition containing the search, filtering, resume-selection, application-material, tracking, and scheduling instructions.

⚠️ Important

The Bangalore, experience-eligibility, and development-only requirements are hard filters. They should not be relaxed automatically simply because a job has a high keyword or skill match.