# bp-influence: Influencer Marketing + PR Teams

A comprehensive Claude Code workspace containing **35 specialist subagents** (25 Influencer + 10 PR) and **24 reusable skills** (18 Influencer + 6 PR) for full-cycle brand communications.

## 🚀 Quick Start

This workspace is ready to use immediately. No setup required — just start delegating to the specialist agents or using the skills.

## 📋 What's Included

### 25 Influencer Marketing Agents
Organized into 8 sections covering the full influencer marketing lifecycle:

- **Strategy & Leadership**: Head of Marketing, Influencer Strategist, Campaign Manager
- **Talent & Relationships**: Talent Scout, Creator Relationship Manager, Outreach Coordinator
- **Content & Creative**: Creative Director, Content Producer, Video Editor, Copywriter
- **Data & Analytics**: Analytics Manager, Data Analyst, Tech Stack Manager
- **Legal & Finance**: Legal Advisor, Brand Safety Manager, Finance Coordinator
- **Paid & Growth**: Paid Social Manager, Affiliate Specialist
- **Community & Communications**: Community Manager, PR Specialist, Social Media Manager
- **Specialist & Emerging**: B2B Specialist, Gaming Specialist, Virtual Influencer Manager, Localisation Manager

### 10 PR Agents
Covering the complete public relations function:

- **Strategy & Crisis**: PR Director, Crisis Communications Manager
- **Media Relations**: Media Relations Manager, Press Secretary, Digital PR Specialist
- **Communications & Content**: Corporate Communications Manager, PR Content Writer
- **Events, Analytics & Reputation**: Event & Launch Coordinator, PR Analytics Specialist, Brand Reputation Manager

### 18 Influencer Skills
Structured templates for common workflows:

- **Campaign Workflows**: `campaign-brief`, `campaign-postmortem`, `campaign-status`
- **Talent Management**: `vet-creator`, `outreach-message`, `ambassador-programme`
- **Content & Creative**: `content-brief`, `content-calendar`, `mood-board`
- **Analytics**: `performance-report`, `roi-calculator`, `benchmark-analysis`
- **Legal & Compliance**: `influencer-contract`, `disclosure-checklist`, `brand-safety-audit`
- **Reference**: `platform-specs`, `rate-card`, `tier-definitions`

### 6 PR Skills

- **Media & Outreach**: `press-release`, `media-pitch`, `media-kit`
- **Events & Crisis**: `event-brief`, `crisis-response-plan`
- **Reporting**: `pr-report`

## 💡 How to Use

### Using Agents
Delegate tasks to specialists by name:

```
Use the influencer-strategist agent to plan a TikTok campaign for our new product launch.
```

```
Use the legal-advisor agent to review this influencer contract draft.
```

```
Use the talent-scout agent to find micro-influencers in the fitness niche.
```

```
Use the crisis-communications-manager agent to build a crisis response plan for a product safety issue.
```

```
Use the media-relations-manager agent to create a Tier 1 media outreach strategy for our product launch.
```

### Using Skills
Invoke templates directly:

```
Use the campaign-brief skill to create a brief for our Summer skincare campaign.
```

```
Use the roi-calculator skill to analyze the ROI of our Q2 influencer programme.
```

```
Use the disclosure-checklist skill to audit our sponsored TikTok content.
```

```
Use the press-release skill to write the announcement for our new partnership.
```

```
Use the crisis-response-plan skill to prepare a playbook for a data breach scenario.
```

### Combining Agents + Skills
For maximum power, combine them:

```
Use the creative-director agent with the mood-board skill to create visual direction for our brand campaign.
```

```
Use the analytics-manager agent with the performance-report skill to analyze our latest campaign results.
```

## 🎯 Common Workflows

### New Campaign Setup
1. `influencer-strategist` → Define strategy and audience
2. `campaign-brief` → Create detailed campaign brief
3. `content-calendar` → Plan posting schedule
4. `mood-board` → Set creative direction
5. `talent-scout` → Identify and vet creators
6. `outreach-message` → Craft outreach templates

### Creator Onboarding
1. `vet-creator` → Comprehensive creator audit
2. `brand-safety-audit` → Risk assessment
3. `influencer-contract` → Generate contract
4. `content-brief` → Deliverable specifications
5. `disclosure-checklist` → Compliance verification

### Campaign Analysis
1. `performance-report` → Post-campaign results
2. `roi-calculator` → Financial analysis
3. `benchmark-analysis` → Industry comparison
4. `campaign-postmortem` → Insights and recommendations

### PR Launch
1. `pr-director` → Define PR strategy and media targets
2. `press-release` → Write the announcement
3. `media-pitch` → Craft personalised journalist pitches
4. `event-brief` → Plan the press event
5. `media-kit` → Prepare press materials
6. `pr-report` → Post-launch coverage analysis

### Crisis Response
1. `crisis-communications-manager` → Activate and lead
2. `crisis-response-plan` → Deploy scenario playbook
3. `press-secretary` → Prepare statements and talking points
4. `brand-reputation-manager` → Monitor and recover

### Cross-Team (Influencer + PR)
1. `pr-director` + `influencer-strategist` → Align PR and influencer narratives
2. `event-launch-coordinator` + `outreach-coordinator` → Joint press + creator event
3. `media-relations-manager` + `pr-specialist` → Earned media + influencer seeding

## 📊 Model Assignment

- **Opus** (Strategic): PR Director, Crisis Comms, Head of Marketing, Creative Director, Legal Advisor
- **Sonnet** (Specialist): Most roles requiring domain expertise
- **Haiku** (Operational): Events, PR Analytics, Outreach, Video Editing, Data Analysis

## 🛠️ Technical Details

- **Framework**: Claude Code subagents and skills
- **Location**: `.claude/agents/` (35 files) and `.claude/skills/` (24 directories)
- **Reference**: [CLAUDE.md](CLAUDE.md) — Complete team guide with tables and examples
- **Version Control**: Git repository initialized with initial commit

## 📈 Getting Started Examples

### Example 1: Campaign Planning
```
Use the influencer-strategist agent to develop a strategy for launching our eco-friendly water bottle on Instagram and TikTok, targeting Gen Z consumers with a $50K budget.
```

### Example 2: Creator Vetting
```
Use the talent-scout agent with the vet-creator skill to evaluate @sustainableliving_influencer for our environmental campaign.
```

### Example 3: Content Creation
```
Use the copywriter agent to create 10 caption variations for our product launch, including hashtags and CTAs for Instagram and TikTok.
```

### Example 4: Performance Analysis
```
Use the analytics-manager agent with the roi-calculator skill to calculate the ROI of our recent influencer campaign, including EMV and halo effects.
```

### Example 5: Crisis Preparation
```
Use the crisis-communications-manager agent with the crisis-response-plan skill to create a playbook for potential product recall scenarios.
```

### Example 6: Press Launch
```
Use the pr-content-writer agent with the press-release skill to write the announcement for our Series B funding, then the media-relations-manager with the media-pitch skill to pitch it to TechCrunch, The Verge, and Wired.
```

## 🔧 Customization

- **Add New Agents**: Create `.claude/agents/new-agent.md` with YAML frontmatter
- **Create Skills**: Add `.claude/skills/new-skill/SKILL.md` with templates
- **Modify Existing**: Edit any agent or skill file directly
- **Team Structure**: Update [CLAUDE.md](CLAUDE.md) to reflect changes

## 📞 Support

This workspace is self-contained and ready to use. For questions about specific agents or skills, refer to their individual files or the [CLAUDE.md](CLAUDE.md) reference guide.

---

**Built for**: Complete influencer marketing + PR operations  
**Agents**: 35 specialists across 12 domains  
**Skills**: 24 reusable workflow templates  
**Ready to use**: No configuration required