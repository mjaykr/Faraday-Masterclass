# Faraday Masterclass 45

Speaker - Dr Andy Sode Anker

Context - Machine Learning/AI analysis methods for scattering/spectroscopy data for battery materials

**Harnessing AI and Machine Learning to Revolutionize Materials Science: Insights from Dr. Andy Sotoranka**  

In a recent webinar, Dr. Andy Sotoranka, Novo Nordisk Foundation Postdoctoral Fellow at DTU and Forbes 30 Under 30 honoree, shared groundbreaking advancements in applying artificial intelligence (AI) and machine learning (ML) to analyze scattering and spectroscopy data. His work bridges the gap between experimental data and structural insights, offering transformative tools for materials scientists. Here’s a breakdown of his key insights.  

---

### **The Challenge: Analyzing Mountains of Experimental Data**  

Modern facilities like synchrotrons and neutron sources generate vast amounts of data—often *tens of thousands of datasets* in a single experiment. Traditional analysis methods, such as structure refinement (e.g., Rietveld refinement), rely on expert intuition and time-consuming trial-and-error to match data to structural models. As Dr. Sotoranka noted:  

> *"In my PhD, I spent months refining structural models. Machine learning can now do this in seconds."*  

---

### **From Fingerprints to Structures: The Power of Supervised ML**  

Dr. Sotoranka likened scattering data to **forensic fingerprints**. Just as detectives compare fingerprints to databases, supervised ML algorithms can screen simulated structural databases to identify matches for experimental data. Key tools developed include:  

- **MetalFinder**: Identifies metals from PDF (Pair Distribution Function) data.  
- **CIF-Finder**: Matches PDFs to metal oxide structures for Rietveld refinement.  
- **POMfinder**: Tailored for polyoxometalates.  

These tools classify data with ~96% accuracy in top-three guesses, slashing analysis time from hours to seconds. However, Dr. Sotoranka emphasized the need for validation:  

> *"ML accelerates discovery, but conventional refinement remains critical for verifying results."*  

---

### **Beyond Databases: Unsupervised Learning and Latent Space**  

What if a structure *isn’t* in the database? Enter **unsupervised learning**. Using autoencoders—neural networks that compress data into a simplified "latent space"—Dr. Sotoranka’s team interpolates between known structures to predict unknown ones. For example:  

- A **probabilistic autoencoder** trained on simulated nanoparticle PDFs learned to map experimental data to atomic coordinates with sub-angstrom accuracy.  
- The tool **Deepstruct** visualizes structures in 2D latent space, allowing users to explore chemical trends and generate plausible models in seconds.  

This approach, dubbed *"AlphaFold for scattering data,"* democratizes structural analysis, enabling non-experts to propose models for validation.  

---

### **Real-World Impact and Future Directions**  

Dr. Sotoranka’s tools are already empowering researchers:  

- **Deepstruct’s public platform** lets users upload PDFs and generate structural hypotheses instantly.  
- **Self-driving laboratories** integrate these models to automate material synthesis and characterization.  

Looking ahead, he envisions **foundation models** (akin to ChatGPT) that unify ML across materials science domains, from spectroscopy to imaging.  

---

### **Try It Yourself!**  

Explore Dr. Sotoranka’s tools:  

- **Deepstruct**: [DeepStruc](https://github.com/EmilSkaaning/DeepStruc) (Upload PDFs to predict structures).  
- **MetalFinder/CIF-Finder**: Available for specialized material screening.  

---

### **Conclusion**  

Dr. Sotoranka’s work exemplifies how AI/ML is reshaping materials science—turning months of labor into minutes of computation. While challenges like experimental-to-simulated data gaps persist, these tools offer a glimpse into a future where *every lab* leverages AI to accelerate discovery.  

*Acknowledgments*: Dr. Sotoranka thanked collaborators at KU, ISIS Neutron Source, and the Scientific Machine Learning Group. 
