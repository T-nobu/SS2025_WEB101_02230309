# Practical 7: Data Visualization Dashboard 📊

## What This Project Is About  
Built a React dashboard using **Recharts** to display different types of charts for data analysis. It’s interactive, responsive, and looks clean thanks to Tailwind CSS.

## Key Features  
- **Monthly Sales**: Line chart comparing sales vs targets  
- **Product Categories**: Pie chart showing market share  
- **Customer Acquisition**: Bar chart for new vs returning customers  
- **Weekly Visitors**: Area chart showing visitor trends  

## Tech Used  
- React 18 with Next.js  
- Recharts for charts  
- TypeScript for type safety  
- Tailwind CSS for styling  

## How It Works  
- Charts use mock data structured for easy visualization  
- Responsive design with Recharts’ `ResponsiveContainer` so charts fit all screen sizes  
- Custom colors and gradients for a professional look  
- Performance optimized with memoization and minimal dependencies  

## Challenges & Tips  
- Make sure Recharts is installed correctly or charts won’t render  
- Use `ResponsiveContainer` to avoid layout issues  
- Keep data structure consistent for charts to display properly  

## How to Run  
1. Clone repo and install dependencies  
2. Run `npm run dev`  
3. Visit `http://localhost:3000` to see the dashboard  

## What I Learned  
- How to integrate multiple chart types in React smoothly  
- Importance of responsive and touch-friendly design for dashboards  
- Performance optimizations like memoizing components to avoid unnecessary re-renders  

## What’s Next?  
- Replace mock data with real API data  
- Add more interactive features like filtering and drill-downs  
- Further customize styles and UX  

## Final Thoughts  
This project was a great way to get hands-on with React data visualization. Recharts made it straightforward to build beautiful, responsive charts, and combining it with Next.js and Tailwind made the whole app fast and scalable.
