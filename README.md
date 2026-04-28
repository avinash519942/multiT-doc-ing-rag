# multiT-doc-ing-rag
Multi-Tenant Document Ingestion &amp; RAG Service - Build a SaaS module that lets each tenant upload documents, organizes them into a logical folder structure, auto-generates rich metadata, and exposes a Retrieval-Augmented Generation (RAG) pipeline for question answering over those documents.  

<H2>DESCRIPTION</H2>
Build a SaaS module that lets each tenant upload documents, organizes them into a logical folder structure, auto-generates rich metadata, and exposes a Retrieval-Augmented Generation (RAG) pipeline for question answering over those documents.	


OBJECTIVE
Deliver a secure, scalable ingestion and RAG pipeline that supports hundreds of tenants, ensures strict data isolation, and surfaces accurate, context-grounded answers from tenant-specific documents, including the sources/actual extract of text from source	

DELIVERABLE 
Web/API upload with drag-and-drop & presigned URLs; Auto folder creation per tenant/project/date; Metadata extraction (title, author, data type, tags); Vector index per tenant (FAISS / Azure AI Search); RAG endpoint with citation links; Terraform + Helm deployment scripts; Postman collection & demo notebook	

TECHNIQUES INVOLVED
Chunking strategies, Metadata generation/management, Vectorization concepts,RAG implementation designs

ARCHITECTURE HINTS



