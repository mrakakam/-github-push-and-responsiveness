vanilla html and css 

/* 📱 Small screens (mobile) */ @media (max-width: 600px)

/* 📱➡️💻 Medium screens (tablet) */ @media (min-width: 601px) and (max-width: 992px)

/* 💻 Large screens (desktop) */ @media (min-width: 993px)



react ( tailwind css) sizes 

sm: → ≥640px

md: → ≥768px

lg: → ≥1024px

xl: → ≥1280px

2xl: → ≥1536px


React + JS Logic (conditional rendering)

{width < 768 ? (
  <p>📱 Mobile layout</p>
) : width < 1024 ? (
  <p>📲 Tablet layout</p>
) : (
  <p>💻 Desktop layout</p>
)}



