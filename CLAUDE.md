# Influencer Team — bp-influence

This workspace contains **25 specialist subagents** representing a complete influencer marketing team. Each agent has domain expertise, specific KPIs, and structured output standards.

## Team Structure

### Section 1: Strategy & Leadership
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 01 | `head-of-influencer-marketing` | Opus | Programme strategy, budgets, C-suite reports, team structure |
| 02 | `influencer-strategist` | Sonnet | Campaign strategies, audience research, platform mix, trends |
| 03 | `campaign-manager` | Sonnet | Timelines, coordination, deliverable tracking, post-mortems |

### Section 2: Talent & Relationships
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 04 | `talent-scout` | Sonnet | Creator discovery, vetting, database building, competitor analysis |
| 05 | `creator-relationship-manager` | Sonnet | Ambassador programmes, loyalty, conflict resolution |
| 06 | `outreach-coordinator` | Haiku | First contact, negotiation, CRM management |

### Section 3: Content & Creative
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 07 | `creative-director` | Opus | Creative vision, briefs, content review, format innovation |
| 08 | `content-producer` | Sonnet | Production assets, calendars, UGC repurposing |
| 09 | `video-editor` | Haiku | Edit briefs, format specs, motion graphics direction |
| 10 | `copywriter` | Sonnet | Creator briefs, captions, hashtags, CTAs |

### Section 4: Data & Analytics
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 11 | `analytics-manager` | Sonnet | KPI dashboards, attribution models, performance reports |
| 12 | `data-analyst` | Haiku | Data pipelines, report templates, A/B tests, tracking |
| 13 | `tech-stack-manager` | Sonnet | Platform evaluation, integrations, vendor management |

### Section 5: Legal, Compliance & Finance
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 14 | `legal-advisor` | Opus | Contracts, FTC/ASA compliance, IP rights, disputes |
| 15 | `brand-safety-manager` | Sonnet | Creator audits, risk assessment, crisis response |
| 16 | `finance-coordinator` | Haiku | Payments, budgets, invoicing, financial reports |

### Section 6: Paid & Growth
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 17 | `paid-social-manager` | Sonnet | Whitelisting, paid amplification, A/B testing, ROAS |
| 18 | `affiliate-specialist` | Sonnet | Commissions, promo codes, fraud detection, revenue attribution |

### Section 7: Community & Communications
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 19 | `community-manager` | Haiku | Engagement, UGC programmes, sentiment, micro-influencer ID |
| 20 | `pr-specialist` | Sonnet | Media pitches, press events, product seeding, EMV |
| 21 | `social-media-manager` | Haiku | Brand channels, cross-posting, editorial calendar, algorithms |

### Section 8: Specialist & Emerging
| # | Agent | Model | Use For |
|---|-------|-------|---------|
| 22 | `b2b-influencer-specialist` | Sonnet | LinkedIn creators, B2B content, pipeline influence |
| 23 | `gaming-specialist` | Sonnet | Twitch/YouTube Gaming, livestream activations, esports |
| 24 | `virtual-influencer-manager` | Sonnet | CGI/AI creators, synthetic content ethics |
| 25 | `localisation-manager` | Sonnet | Regional adaptation, multi-language, cross-market comparison |

## How to Use

Ask Claude to delegate to the appropriate specialist:

```
Use the influencer-strategist agent to build a TikTok campaign strategy for our Q3 product launch.
```

```
Use the legal-advisor agent to draft an influencer contract template with exclusivity clauses.
```

```
Use the talent-scout agent to create a vetting checklist for beauty micro-influencers.
```

You can also chain agents for multi-step workflows:

```
Use the influencer-strategist to plan the campaign, then the creative-director to write the brief,
then the copywriter to draft caption frameworks.
```

## Skills (Reusable Workflows & Templates)

Skills are structured templates that any agent (or you directly) can invoke. Use them by name:

```
Use the campaign-brief skill to create a brief for our Summer 2025 skincare launch on TikTok and Instagram.
```

### Campaign Workflows
| Skill | Description |
|-------|-------------|
| `campaign-brief` | Full campaign brief generator — 10 sections from overview to legal |
| `campaign-postmortem` | Post-campaign analysis with repeat/refine/remove/test framework |
| `campaign-status` | Weekly status report with traffic-light system and blocker tracking |

### Talent & Creator Management
| Skill | Description |
|-------|-------------|
| `vet-creator` | 7-section creator vetting report with composite scoring |
| `outreach-message` | DM, email, and follow-up templates with personalisation checklist |
| `ambassador-programme` | 4-tier ambassador programme designer (Bronze → Platinum) |

### Content & Creative
| Skill | Description |
|-------|-------------|
| `content-brief` | Detailed creator content brief — deliverable-level instructions |
| `content-calendar` | Editorial calendar with posting sequence, repurposing map |
| `mood-board` | Visual direction document — colours, typography, tone, references |

### Analytics & Reporting
| Skill | Description |
|-------|-------------|
| `performance-report` | Full campaign performance report with creator breakdown |
| `roi-calculator` | ROI/ROAS calculation with EMV, halo effects, scenario modelling |
| `benchmark-analysis` | Industry benchmark comparison by tier, platform, and competitor |

### Legal & Compliance
| Skill | Description |
|-------|-------------|
| `influencer-contract` | Complete contract framework — deliverables, payment, IP, termination |
| `disclosure-checklist` | FTC/ASA/global disclosure compliance audit checklist |
| `brand-safety-audit` | Full creator brand safety assessment with risk scoring |

### Reference & Lookup
| Skill | Description |
|-------|-------------|
| `platform-specs` | Technical specs for all platforms — formats, sizes, algorithm signals |
| `rate-card` | Market rate benchmarks by tier/platform + negotiation framework |
| `tier-definitions` | Influencer tier classification, characteristics, and strategic mix |

## Combining Agents + Skills

For maximum power, combine an agent with a skill:

```
Use the creative-director agent with the mood-board skill to create visual direction for our Festival campaign.
```

```
Use the legal-advisor agent with the disclosure-checklist skill to audit our latest TikTok batch.
```

```
Use the analytics-manager agent with the roi-calculator skill to build the business case for scaling our Q2 programme.
```

## Model Assignment Rationale

- **Opus** — Strategic leadership and high-stakes decisions (Head of Marketing, Creative Director, Legal)
- **Sonnet** — Core specialist work requiring domain expertise (most roles)
- **Haiku** — High-volume operational tasks (Outreach, Video Editing, Data Analyst, Community, Social)
