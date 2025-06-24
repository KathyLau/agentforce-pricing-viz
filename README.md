# Salesforce Agentforce Pricing Comparison Tool

**Created by Kathy Lau, AI Architect, Partner Success Team**

## Overview

This interactive web tool helps organizations compare and analyze the cost implications of different Salesforce Agentforce pricing models. It provides real-time calculations, visual comparisons, and breakeven analysis to help you make informed decisions about which pricing model best fits your organization's needs.

## What This Tool Shows

### Pricing Models Compared

The tool compares three Salesforce Agentforce pricing models:

1. **Flex Credits** - Pay-per-action model at $0.10 per action
2. **Legacy Pricing** - Fixed rate of $2.00 per conversation/topic
3. **Agentforce 1 Edition** - Subscription model at $550 per user per month

### Key Features

#### Interactive Controls
- **Number of Users**: Adjust from 1 to 500 users
- **Volume of Agent Topics per Month**: Set from 0 to 100,000 topics
- **Average Actions Per Topic**: Configure from 1 to 50 actions per topic

#### Visual Analytics
- **Cost Per Topic Overview**: Real-time infographic showing cost breakdown per topic for each pricing model
- **Interactive Line Chart**: Dynamic visualization showing how costs scale with topic volume
- **Monthly Cost Summary**: Current cost calculations for your selected parameters

#### Intelligent Analysis
- **Breakeven Analysis**: Automatically calculates when each pricing model becomes most cost-effective
- **Key Insights**: Guidance on when to use each pricing model based on usage patterns
- **Dynamic Recommendations**: Real-time advice based on your current parameter selections

## How to Use

1. **Set Your Parameters**: Use the sliders to input your organization's expected usage:
   - Number of users who will interact with Agentforce
   - Expected monthly volume of agent conversations/topics
   - Average number of actions each topic will require

2. **Review Cost Comparisons**: 
   - Check the "Cost Per Topic Overview" for immediate per-topic cost insights
   - Review the "Current Monthly Costs" section for total monthly expenses
   - Examine the interactive chart to see how costs scale with volume

3. **Analyze Breakeven Points**: 
   - Read the breakeven analysis to understand when each model becomes most economical
   - Use the key insights to determine which model aligns with your usage patterns

## Understanding the Results

### When Flex Credits Are Most Cost-Effective
- Topics typically require fewer than 20 actions
- Variable or unpredictable usage patterns
- Lower overall monthly volume of actions
- Need for cost transparency based on exact usage

### When Agentforce 1 Edition Is Most Cost-Effective
- High volume usage (thousands of topics per month)
- Predictable and consistent usage patterns
- Teams need unlimited access without action count concerns
- Budget predictability with fixed monthly costs is prioritized

### Key Breakeven Insight
The tool automatically calculates that Flex Credits become more expensive than Legacy Pricing when topics consistently require 20 or more actions (since $0.10 × 20 actions = $2.00, matching the Legacy rate).

## Technical Details

### Built With
- **HTML5/CSS3**: Responsive design with Salesforce brand colors
- **JavaScript**: Interactive calculations and real-time updates
- **Chart.js**: Dynamic data visualization
- **Responsive Design**: Works on desktop and mobile devices

### Calculations
- **Flex Credits**: `Actions per Topic × $0.10 × Total Topics`
- **Legacy Pricing**: `$2.00 × Total Topics`
- **Agentforce 1 Edition**: `$550 × Number of Users`

### File Structure
```
agentforce-pricing-tool/
├── index.html          # Main application file
├── README.md          # This documentation
└── assets/            # (Optional) Additional resources
```

## Use Cases

This tool is ideal for:
- **Solution Architects** planning Agentforce implementations
- **Finance Teams** budgeting for AI automation initiatives
- **IT Leaders** comparing cost models for different usage scenarios
- **Partners** demonstrating value propositions to clients
- **Sales Teams** providing accurate pricing guidance

## Best Practices

1. **Conservative Estimation**: Start with conservative action counts and gradually increase based on actual usage patterns
2. **Scenario Planning**: Test multiple scenarios (low, medium, high usage) to understand cost implications
3. **Regular Review**: Revisit calculations as your Agentforce implementation matures and usage patterns become clearer
4. **Consider Growth**: Factor in potential growth in users and topics when making long-term decisions

## Limitations

- Pricing information is based on standard Salesforce rates and may not reflect custom enterprise agreements
- The tool assumes consistent usage patterns; actual usage may vary
- Additional costs such as data storage, integrations, or custom development are not included
- Prices are subject to change based on Salesforce's current pricing policies

## Support and Feedback

For questions about this tool or Agentforce pricing guidance, please contact the Partner Success Team or refer to official Salesforce documentation.

---

*This tool is designed to provide pricing estimates for planning purposes. Always consult with your Salesforce account team for official pricing and contract terms.*
