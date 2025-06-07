# Practical 7: Data Visualization Reflection 🤔

## What I Worked On  
Built a React dashboard with reusable chart components using Recharts. Focused on responsive, interactive visuals with good performance.

## Key Concepts Applied  
- **React Components**: Modular design, managing props and state, composing charts into one dashboard  
- **Chart Types**: Picked charts to fit data — line for trends, pie for parts, bar for comparisons, area for volumes  
- **Recharts Features**: Responsive containers, custom colors & gradients, tooltips, legends  
- **Performance**: Memoization, static data outside components, efficient rendering  
- **Responsive Design**: Mobile-first, CSS Grid layout, touch-friendly elements  

## What I Learned  
- Recharts fits React better than some other libraries  
- Importance of color psychology, visual hierarchy, and accessibility  
- How to optimize React rendering and manage memory  
- UX matters — interactive feedback and consistent experience across devices  

## Challenges & How I Fixed Them  
1. **Charts not resizing properly** → Wrapped charts in `ResponsiveContainer` and used CSS for sizing  
2. **Wrong data structure** → Changed data to arrays of objects as Recharts expects  
3. **Styling too hard** → Used Recharts’ built-in styling with gradients instead of overriding CSS  
4. **Performance issues with big data** → Used data sampling, lazy loading, and React.memo to speed up  
5. **Basic tooltips lacking info** → Customized tooltips for clearer, formatted data  

## Important Takeaways  
- Picking the right library impacts speed and quality  
- Clean, well-structured data is key to good visuals  
- Visualizations should focus on user needs, not just tech  
- Balancing features and performance is essential  
- Responsiveness requires more than flexible containers — rethink data for different screens  

## What’s Next  
- Add real-time data updates with WebSockets  
- Enable drill-downs, filtering, and data export  
- Improve accessibility (screen readers, keyboard nav, contrast)  
- Further optimize performance for large datasets  

## Final Thoughts  
This project taught me that data visualization is storytelling. It’s not just about showing numbers, but making them understandable and actionable — by choosing the right charts, styling smartly, ensuring smooth interaction, and keeping performance tight.
