# ZEAB Repository - Claude Instructions

## File Format Preferences

When working with documents in this repository, prefer git-friendly formats where practical for better version control.

### Recommended Approach

#### For New Documents
- **Prefer Markdown (.md)** when creating new documents or reports
- Use CSV for simple data tables when possible
- Use text-based formats for better git tracking

#### For Existing Documents
- Work with whatever format exists
- If making substantial edits to a binary file, consider creating a Markdown companion document
- Don't convert files unless it adds value

### Repository Structure

The repository is organized into the following main directories:
- **Administration/** - Meeting notes, legislation tracking
- **Plans & Strategies/** - Climate action plans, net zero strategies, BERDO
- **Initiatives/** - Building, energy, and transportation initiatives
- **Analysis & Data/** - Energy, financial, and market analyses
- **Documentation/** - Repository documentation and guides
- **Scripts/** - Automation and analysis scripts

## Guidelines for Claude

1. **Prefer Markdown** when creating new documents unless requested to do otherwise
2. **Suggest but don't force** text formats when appropriate
3. **Work with existing formats** without requiring conversion
4. **Use Markdown for reports** you generate
5. **Respect user preferences** for file formats
6. All documents that you create or edit should be marked as DRAFT and indicate that they were authored or edited by AI
7. **All generated documents must include proper citations with hyperlinks to credible sources**
8. **Prioritize credible sources in all research and analysis**

### DRAFT Document Formatting Requirements

When marking documents as DRAFT:
- Use **extra large bold headers** for maximum visibility: `# **🚧 DRAFT 🚧**`
- Place at the very top of the document
- Follow with clear status information in bold
- Include AI authorship/editing notice
- Use construction/warning emojis for visual emphasis

Example format:
```markdown
# **🚧 DRAFT 🚧**

**Status**: DRAFT - Under Review
**Note**: This document was generated/edited by AI and requires human review for accuracy.

---

# [Actual Document Title]
```

### Research and Citation Requirements

When generating documents or conducting research:

#### Source Credibility Hierarchy (use in order of preference):
1. **Government sources** (.gov domains)
   - Federal agencies (EPA, DOE, NREL, etc.)
   - State and local government reports
   - Official policy documents and regulations

2. **Academic and research institutions** (.edu domains)
   - University research centers
   - Peer-reviewed academic papers
   - Research institute publications

3. **Established research organizations**
   - National laboratories (NREL, LBNL, etc.)
   - Non-profit research organizations (RMI, ACEEE, etc.)
   - Professional associations and standards bodies

4. **Industry reports** (use with caution)
   - Only from established, reputable organizations
   - Verify data against government/academic sources
   - Note potential conflicts of interest

#### Citation Requirements:
- **All factual claims must be cited** with hyperlinks to original sources
- Use Markdown link format: `[Description](https://url.com)`
- Include access dates for web sources when relevant
- Prefer primary sources over secondary reporting
- When using data, cite the original data source, not news articles about it

#### Research Quality Standards:
- **Verify data across multiple credible sources** when possible
- **Flag any uncertainties or limitations** in the data
- **Avoid blog posts, opinion pieces, and marketing materials** as primary sources
- **Cross-reference controversial or surprising claims** with authoritative sources
- **Note when data is outdated** and seek more recent information

#### Example Citation Format:
```markdown
According to the EPA's 2023 Greenhouse Gas Inventory, [transportation accounts for 29% of U.S. greenhouse gas emissions](https://www.epa.gov/ghgemissions/sources-greenhouse-gas-emissions).

The National Renewable Energy Laboratory reports that [solar costs have declined 85% since 2010](https://www.nrel.gov/analysis/tech-lcoe-documentation.html), making it cost-competitive with fossil fuels in many markets.
```