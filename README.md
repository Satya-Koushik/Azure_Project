# Azure_Project

# Multi-Region Web Application Deployment Using Azure Traffic Manager and Application Gateway

## Problem Statement
A corporation needs to deploy a multi-page website across two Azure regions with high availability, secure storage, and smart traffic routing. The site includes a home page, an upload page that stores files in Azure Blob Storage, and custom error pages for 403 and 502 errors. Traffic should be distributed optimally using Azure Traffic Manager and routed appropriately using Application Gateway.

## Project Description
To meet the requirements, this project sets up Azure Virtual Machines in the Central US and West US regions to host a multi-page website. The upload functionality is integrated with Azure Blob Storage. Application Gateway is configured for path-based routing and custom error handling, while Azure Traffic Manager ensures global, region-aware traffic distribution and high availability.

## Tools & Services
- Azure Virtual Machines (VM1 hosts the upload page, VM2 hosts the home page)  
- Azure Blob Storage (for static website hosting and an upload container)  
- Azure Application Gateway  
- Azure Traffic Manager  
- Azure Virtual Networks (VNets) & VNet Peering  

## Key Skills
- Deploying and managing Azure VMs and running deployment scripts  
- Integrating Azure Blob Storage with applications  
- Configuring Application Gateway for routing and custom error handling  
- Setting up and optimizing Azure Traffic Manager for global traffic distribution  
- Establishing VNet Peering between Azure regions  
- Designing for multi-region high availability  
