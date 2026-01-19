# AI_WhatsApp_Appointment_Workflow_n8n
AI whatsapp based appointment workflow via n8n for hospitals and clinics.

**How the system works:**
A patient sends a simple message like: “I want to book an appointment with a cardiologist for Tuesday.”
The AI agent understands the intent, specialty, and preferred day, the workflow automatically checks:
*Doctor availability.
*Day-wise schedules.
*Time slots.
*Consultation fees (from structured data / Google Sheets).
*If doctor available, the system confirms the appointment.
*If doctor not available, the patient is informed instantly.
*Internal confirmation is sent to the hospital/admin team.

**Key technologies used:**
1-WhatsApp Business Cloud API.
2-n8n workflow automation.
3-AI / LLM-based intent & data extraction.
4-Structured JSON doctor schedules.
5-Google Sheets as a lightweight database.

**Business impact:**
*Reduces front-desk workload.
*24/7 appointment booking.
*Faster response time.
*No missed leads.
*Scalable for clinics, hospitals, and service-based businesses.
