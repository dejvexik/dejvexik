class DejvexDeveloper:
    def __init__(self):
        self.name = "Dejvex"
        self.aliases = ["DX SCRIPT"]
        self.role = "Full Stack Developer"
        self.passion = "Creating elegant solutions to complex problems"
        
    def skills(self):
        return {
            'frontend': ['React', 'Vue', 'TypeScript', 'Tailwind'],
            'backend': ['Node.js', 'Python', 'PHP', 'SQL'],
            'tools': ['Git', 'Docker', 'VS Code', 'Figma'],
            'learning': ['AI/ML', 'Cloud Architecture', 'System Design']
        }
    
    def motto(self):
        return "Code with purpose, design with passion"

dev = DejvexDeveloper()
