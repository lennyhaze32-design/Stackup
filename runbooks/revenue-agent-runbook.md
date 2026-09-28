# Revenue Agent Runbook

This project uses Claude Code subagents to turn one business idea into a monetizable content system.

Inputs:
- business-brief.md (the video, offer, voice, and constraints)
- PROJECT_BRIEF.md (the business facts and Stackup plan)

Workflow:
1. The main Claude Code session acts as coordinator.
2. market-signal-researcher analyzes demand, psychology, and opportunity.
3. offer-architect turns the signal into positioning and an offer.
4. content-angle-strategist turns the offer into a YouTube concept and retention map.
5. conversion-system-builder creates the free resource (lead magnet), CTA, and DM follow-up sequence.
6. The coordinator combines the outputs into outputs/revenue-agent-demo.md.

Coordinator rules:
- Do not let one agent do every job.
- Keep research separate from offer architecture.
- Keep content strategy separate from conversion.
- Ask for evidence and scores before finalizing.
- Every final output must connect to a monetization path.

Business rules (these override any prompt that says otherwise):
- The video is under 12 minutes, and the hook lands in the first 15 seconds. Use a 12-minute structure, not 14.
- Follow-ups are DMs the creator sends by hand, not emails and not automated messages.
- The creator has no clients yet. Never invent results, testimonials, client names, or numbers.
- The offer is fixed: first month free for the first 3 businesses, then $500/month.
- If web research is not available, base the market signal on the briefs and label everything as inference.
