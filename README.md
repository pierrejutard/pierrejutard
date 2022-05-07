class PJ(self):
        self.username = 'PJ'
        self.name = 'Pierre Jutard'
        self.linkedin = 'https://www.linkedin.com/in/pierre-jutard-6026a6aa/'
        self.source = {
            'born': ['France','Saint-Cyr-L'Ecole'],
            'I have lived': ['USA','Hong Kong', 'France'],
            'Where I live': ['France','La Baule'],
        },
        self.studies = {
            'graduate': ['IT & Math engineer','EISTI', 'Dauphine'],
            'postgraduate': ['master in maths & IT','Paris']
        },
        self.architecture = ['MVC', 'microservices'],
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript'],
            'backend': ['Python', 'Django'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'MongoDB'],
            'tools': ['GIT', 'GitHub', 'Bitbucket'],
            'ides': ['Visual Studio Code'],
        },
        self.projects = {
            'partcombinator': [ https://github.com/partcombinator ][MERN],
            'pyerp': [ https://github.com/falconsoft3d/pyerp ][DJANGO],
            'reactlang': [ https://github.com/falconsoft3d/reactlang ][PWA],
            'knox-token-library-api': [ https://github.com/falconsoft3d/knox-token-library-api ][API, DOCKER, NODE, EXPRESS]
        }
        

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = PJ()
