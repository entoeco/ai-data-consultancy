export const metadata = {
  title: "Projects | Robert Fowler Consulting",
  description:
    "Selected projects across technical operations leadership, data analysis, automation, and applied AI.",
};

const projects = [
  {
    title: "Facility Billing & Pricing Automation",
    blurb:
      "Designed a tiered pricing and billing workflow to support mixed research and commercial use, improving auditability and reducing manual effort.",
    image: "/projects/billing.png",
  },
  {
    title: "Incident & Training Data Analysis",
    blurb:
      "Exploratory analysis to test relationships between training completion and incident occurrence using statistical modelling and clear visualisation.",
    image: "/projects/incident-model.png",
  },
  {
    title: "AI Email & Document Triage Pilot",
    blurb:
      "Prototype AI-assisted workflow to categorise incoming requests, extract key information, and support prioritisation with governance safeguards.",
    image: "/projects/ai-triage.png",
  },
];

export default function ProjectsPage() {
  return (
    <main style={{ padding: "3rem", maxWidth: "1100px", margin: "0 auto" }}>
      <h1>Projects</h1>
      <p style={{ maxWidth: "700px" }}>
        A small selection of work spanning technical operations leadership,
        data analysis, automation, and applied AI.
      </p>

      <div
        style={{
          display: "grid",
          gridTemplateColumns: "repeat(auto-fit, minmax(280px, 1fr))",
          gap: "2rem",
          marginTop: "2rem",
        }}
      >
        {projects.map((p) => (
          <div
            key={p.title}
            style={{
              border: "1px solid #e5e7eb",
              borderRadius: "12px",
              overflow: "hidden",
              background: "white",
            }}
          >
            <img
              src={p.image}
              alt={p.title}
              style={{ width: "100%", height: "180px", objectFit: "cover" }}
            />
            <div style={{ padding: "1rem" }}>
              <h3>{p.title}</h3>
              <p>{p.blurb}</p>
            </div>
          </div>
        ))}
      </div>
    </main>
  );
}

