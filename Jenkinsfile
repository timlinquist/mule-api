def UPSTREAM_PROJECTS_LIST = [ "Mule-runtime/metadata-model-api/support/1.1.7",
                               "Mule-runtime/mule-artifact-declaration/1.1.3-MARCH" ]

Map pipelineParams = [ "upstreamProjects" : UPSTREAM_PROJECTS_LIST.join(','),
                       "mavenSettingsXmlId" : "mule-runtime-maven-settings-MuleSettings",
                       "projectType" : "Runtime" ]

runtimeBuild(pipelineParams)
