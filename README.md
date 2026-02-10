# 🎯 TrainWithShubham Interview Questions Repository

Welcome to the **TrainWithShubham Community Interview Questions Repository**! This repository is a collaborative collection of real interview questions asked by top tech companies, contributed by our amazing community members.

## 📋 Purpose

This repository serves as:
- A centralized database of **real interview questions** from various companies
- A learning resource for students and professionals preparing for DevOps/Cloud interviews
- A **CSV-based data source** that powers the TrainWithShubham community website
- A contribution platform where community members can share their interview experiences

## 🌐 How It Works

Our community website dynamically fetches interview questions from this GitHub repository. The questions are stored in CSV format, making it easy to:
- Parse and display on the website UI
- Filter by company, role, experience level, or topic
- Keep the data version-controlled and transparent
- Allow community contributions via Pull Requests

## 📂 Repository Structure

```
interview-questions/
├── devops/
│   └── devops-interview-questions.csv
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

## 📊 CSV Structure

Each CSV file contains the following columns:

| Column | Description | Example |
|--------|-------------|---------|
| `company` | Name of the company | Amazon, Google, Microsoft |
| `year` | Year of interview | 2024, 2023 |
| `contributor` | GitHub username of contributor | @johndoe |
| `role` | Job role interviewed for | DevOps Engineer, SRE |
| `experience` | Experience level required | 1-2 years, 3-5 years, 5+ years |
| `topic` | Technical topic/category | Docker, Kubernetes, AWS, CI/CD |
| `question` | The actual interview question | Explain the difference between... |

## 🚀 Topics Covered

### DevOps
- 🐳 **Docker** - Containerization, image optimization, Docker Compose
- ☸️ **Kubernetes** - Deployments, Services, StatefulSets, Helm
- 📜 **Shell Scripting** - Automation, monitoring, system administration
- 🔄 **CI/CD** - Jenkins, GitHub Actions, GitLab CI, Azure DevOps
- ☁️ **AWS** - EC2, S3, VPC, Load Balancers, Lambda
- 🛠️ **Configuration Management** - Ansible, Terraform, Chef, Puppet
- 📊 **Monitoring** - Prometheus, Grafana, ELK Stack, CloudWatch

## 🤝 How to Contribute

We welcome contributions from the community! If you've recently attended an interview or want to share questions you've faced, please contribute.

**Quick Steps:**
1. Fork this repository
2. Add your questions to the appropriate CSV file
3. Follow the formatting guidelines in [CONTRIBUTING.md](CONTRIBUTING.md)
4. Submit a Pull Request

For detailed contribution guidelines, please read [CONTRIBUTING.md](CONTRIBUTING.md)

## 📈 Data Usage

### For Developers (Website Integration)

The CSV files can be directly fetched from GitHub using raw URLs:

```javascript
// Example: Fetch DevOps questions
const url = 'https://raw.githubusercontent.com/Nandan29300/interview-questions/main/devops/devops-interview-questions.csv';

fetch(url)
  .then(response => response.text())
  .then(data => {
    // Parse CSV and display in your UI
    console.log(data);
  });
```

### Using GitHub API

```bash
curl https://raw.githubusercontent.com/Nandan29300/interview-questions/main/devops/devops-interview-questions.csv
```

## 🎓 For Students

- Browse questions by company or topic
- Filter by experience level to find relevant questions
- Learn from real interview experiences shared by the community
- Prepare effectively for your next interview

## 🌟 Community

This repository is maintained by the **TrainWithShubham** community. Join us:
- 🐦 Twitter: [@TrainWithShubham](https://twitter.com/trainwithshubham)
- 💼 LinkedIn: [TrainWithShubham](https://linkedin.com/in/shubhamlondhe1996)
- 📺 YouTube: [TrainWithShubham](https://www.youtube.com/@TrainWithShubham)
- 🌐 Website: [trainwithshubham.com](https://trainwithshubham.com)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

A huge thank you to all our contributors who have shared their interview experiences to help others in the community!

---

**Made with ❤️ by the TrainWithShubham Community**

⭐ Star this repository if you find it helpful!
Community contributed interview questions for TrainWithShubham website.
