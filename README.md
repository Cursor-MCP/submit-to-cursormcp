# 🚀 Submit to cursormcp.net

Welcome to the official submission repository for [cursormcp.net](https://cursormcp.net) - the premier marketplace for MCP (Model Context Protocol) servers!

## 🌟 About cursormcp.net

cursormcp.net is a comprehensive marketplace that helps developers discover, share, and integrate MCP servers for enhanced AI assistant capabilities. Our platform showcases high-quality, open-source MCP servers across various categories to empower the AI development community.

## 📋 How to Submit Your MCP Server

We welcome submissions of high-quality, open-source MCP servers! Follow these simple steps:

1. **Click** the [Issues] tab above
2. **Select** "New issue" 
3. **Choose** the "🚀 Submit New MCP Server" template
4. **Fill out** all required information carefully
5. **Submit** your issue - our team will review and process it promptly!

## ✅ Submission Requirements

To ensure quality and usability, your MCP server must meet these criteria:

### **Essential Requirements**
- ✅ **Open Source**: Must have an open-source license
- ✅ **Documentation**: Comprehensive README with clear installation and usage instructions
- ✅ **Functionality**: Fully functional and tested MCP server
- ✅ **Maintenance**: Actively maintained repository

### **Required Information**
When submitting, please provide:

- **Name**: Your MCP server's name
- **Description**: Clear explanation of functionality and features
- **Repository URL**: Link to your open-source repository
- **Category**: Select from our predefined categories
- **Configuration**: Complete MCP server configuration details
- **Glama Link** (optional): If listed on Glama platform

### **Configuration Format**
Provide your MCP server configuration in the standard format:

#### uvx
```json
{
  "mcpServers": {
    "your-server-name": {
      "command": "uvx",
      "args": ["your-mcp-server-package"]
    }
  }
}
```

#### docker
```json
{
  "mcpServers": {
    "your-server-name": {
      "command": "docker",
      "args": ["run", "-i", "--rm", "your-docker-image"]
    }
  }
}
```

#### npm
```json
{
  "mcpServers": {
    "your-server-name": {
      "command": "npx",
      "args": ["-y", "your-mcp-server-package"]
    }
  }
}
```

#### Python
```json
{
  "mcpServers": {
    "your-server-name": {
      "command": "python",
      "args": ["-m", "your_mcp_server_module"]
    }
  }
}
```

#### Node.js
```json
{
  "mcpServers": {
    "your-server-name": {
      "command": "node",
      "args": ["/path/to/your/server.js"]
    }
  }
}
```

#### Binary Executable
```json
{
  "mcpServers": {
    "your-server-name": {
      "command": "/path/to/your/executable",
      "args": ["--option1", "value1"]
    }
  }
}
```

#### Environment Variables (Optional)
```json
{
  "mcpServers": {
    "your-server-name": {
      "command": "uvx",
      "args": ["your-mcp-server-package"],
      "env": {
        "API_KEY": "your-api-key",
        "DEBUG": "true"
      }
    }
  }
}
```


## 🏷️ Categories

We organize MCP servers into the following categories:

- **Developer Tools** - Code execution, version control, testing
- **Productivity** - File management, automation, project management
- **Data Science Tools** - Data analysis, visualization, ML tools
- **Communication** - Chat, email, collaboration tools
- **Cloud Platforms** - AWS, Azure, GCP integrations
- **Databases** - Database connections and management
- **Security** - Authentication, encryption, security tools
- And many more...

## 🔄 Review Process

1. **Submission**: Submit via GitHub issue template
2. **Review**: Our team reviews for quality and compliance
3. **Testing**: We verify documentation
4. **Approval**: Approved servers are added to cursormcp.net
5. **Publication**: Your MCP server goes live on the marketplace!

## 🤝 Contributing Guidelines

- Ensure your MCP server follows [MCP protocol standards](https://modelcontextprotocol.io/)
- Include comprehensive documentation and examples
- Test your server thoroughly before submission
- Maintain your repository and respond to issues
- Follow semantic versioning for updates

## 📞 Support

Need help with your submission? 

- 📧 Create an issue in this repository
- 🌐 Visit [cursormcp.net](https://cursormcp.net) for more information
- 📚 Check out the [MCP documentation](https://modelcontextprotocol.io/)

## 📄 License

This repository is licensed under the [MIT License](LICENSE).

---

**Thank you for contributing to the MCP ecosystem!** 🎉

Together, we're building a vibrant community of AI-powered tools and services.
