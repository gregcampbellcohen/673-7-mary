### 1. Data Source
I'll be using The World Bank's Open Data - specifically, their tracking of Current health expenditure (% of GDP). The data is available here: https://data.worldbank.org/indicator/SH.XPD.CHEX.GD.ZS
### 2. Topic and geographic phenomena your map will explore
I'll be showing health expenditure as a % of GDP from 2000-present. The tentative title is Healthcare Costs as a % of GDP Over Time.
### 3. Map objectives and user needs
Life expectancy in the US quite poor relative to other highly developed countries due to a combination of factors, largely stemming from poor diet, a lack of exercise, overprescribed pharmaceuticals, and, importantly, very poor and expensive healthcare. People have a vague sense that we are unhealthy, but I don't think it's really fully understood. A few political campaigns have cleaned up some of the more absurd arguments I've dealt with, i.e. it only works in small countries, America is too rural, and so on, but it's unusual to hear the % of our cumulative wealth that goes towards healthcare, and many folks are very surprised when they learn how much more we spend relative to our peers. I think budget liens are a perfect place for mapping projects, because absent comparisons, any number over maybe 1 million sounds exactly the same as any other. I've always appreciated international comparisons with other highly developed countries as a tool for demonstrating a point, often because it is unflattering, and that is my point. I work in environmental health advocacy, and I think tools like this can help legislators wrap their heads around crises.

The persona using this map is James. James is a dilettante who has a very basic grasp on a lot of political discussions, and is enthusiastic about learning more. When people talk about things like environmental health or single-payer healthcare, he understands that there are a lot of people clamoring for change, and he might even agree with them in the abstract, but he doesn't understand why we can't just make these changes slowly. He was on his parents' healthcare up until he was 26, and by the time he was off of it Deloitte was picking up the tab. James' parents are conservative, and while he doesn't think of himself that way, he is concerned about things like the national debt. This map is for James.

Users can interact with the map with a time slider. We're going to be using that so they can see the costs go up and up and up over time.

### 4. Anticipated methods of thematic representation
I will be making a chloropleth map using natural breaks.

### 5. Anticipated user interface
I think the data more or less speaks for itself here, and I am under some pretty extreme time constraints, so this will be fairly simple. There will be a sidebar with an explainer on why health expenditure as a % of GDP is a useful metric for determining the cost of a healthcare system, how much the US spends, and our health outcomes. The map will be available on the right of the sidebar, with every country's health expenditure as a % of the GDP featured as the primary attribute, and the one by which the chloropleth map breaks down from a tasteful green to a hideous red. Additionally, there will be a mouseover function that tells you what the % cost is, as well as infant mortality and life expectancy. We will have a slider that allows you to change years, a title, and a legend.

### 6. Technology stack

This will look a lot like the technology stack from week 3: a data folder with a CSV and JSON file, plus Leaflet and, of course, HTML and CSS.