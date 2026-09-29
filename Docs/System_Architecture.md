# TransitIQ System Architecture

## Proposed Production Flow

Bus-mounted camera and GPS sources provide road imagery and vehicle telemetry.

```text
Camera + GPS
     ↓
Edge Detection / AI
     ↓
Issue Classification
     ↓
Severity + Confidence
     ↓
Location + Route Context
     ↓
Backend API
     ↓
Geospatial Database
     ↓
Control-Room Dashboard
     ↓
Alerts / Assignment
     ↓
Resolution
     ↓
Analytics
```

## Important Scope Note

The current browser prototype demonstrates the dashboard and monitoring workflow using simulated/sample data. The production backend, trained edge model, live GPS feeds and database are proposed extensions rather than completed components of this prototype.
