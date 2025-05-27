{\rtf1\ansi\ansicpg1252\cocoartf2821
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue-Bold;\f1\fnil\fcharset0 HelveticaNeue;\f2\fnil\fcharset0 Menlo-Regular;
\f3\fnil\fcharset0 Menlo-Bold;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid2\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li1440\lin1440 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid102\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li1440\lin1440 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid202\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li1440\lin1440 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid302\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li1440\lin1440 }{\listname ;}\listid4}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab560
\pard\pardeftab560\partightenfactor0

\f0\b\fs40 \cf0 Docker vs Kubernetes \'96 Key Differences and Architecture.md\
\pard\pardeftab560\slleading20\partightenfactor0

\fs26 \cf0 \
\pard\pardeftab560\sa40\partightenfactor0

\fs32 \cf0 Docker \'96 Container Platform\
\pard\pardeftab560\slleading20\partightenfactor0

\fs26 \cf0 \
\pard\pardeftab560\slleading20\partightenfactor0

\f1\b0 \cf0 Docker is called a 
\f0\b container platform
\f1\b0  because it enables application packaging into lightweight, portable containers that can run on a single host. However, it comes with some limitations:\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls1\ilvl0
\f2\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f1\fs26 Docker runs on a 
\f0\b single host
\f1\b0 , and if that host or any critical container goes down, the entire application could be affected.\
\ls1\ilvl0
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 It 
\f0\b does not support
\f1\b0  key enterprise-level features such as:\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls1\ilvl1
\f2\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f1\fs26 Auto-scaling\
\ls1\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 Auto-healing\
\ls1\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 Load balancing\
\ls1\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 API gateway integration\
\ls1\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 Firewall management\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 Because of these limitations, Docker alone is generally 
\f0\b not used in production environments
\f1\b0 , especially for large infrastructure needs.\
\
\pard\pardeftab560\sa40\partightenfactor0

\f3\b\fs32 \cf0 \uc0\u9819 \u65039 
\f0  Kubernetes \'96 Container Orchestration Tool\
\pard\pardeftab560\slleading20\partightenfactor0

\f1\b0\fs26 \cf0 Kubernetes is a 
\f0\b container orchestration tool
\f1\b0  that addresses the shortcomings of Docker by ensuring application stability and scalability. For example:\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls2\ilvl0
\f2\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f1\fs26 If a 
\f0\b pod
\f1\b0  (a group of one or more containers) goes down, Kubernetes automatically brings up a replacement pod to keep the application running.\
\ls2\ilvl0
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 It supports:\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls2\ilvl1
\f2\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Auto-scaling
\f1\b0  \'96 to manage load dynamically.\
\ls2\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Auto-healing
\f1\b0  \'96 to ensure availability and stability.\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 Kubernetes is typically installed as a 
\f0\b cluster
\f1\b0 , which is a group of nodes that work together to run containerized applications.\
\
\pard\pardeftab560\sa40\partightenfactor0

\f0\b\fs32 \cf0 Kubernetes Architecture\
\pard\pardeftab560\slleading20\partightenfactor0

\fs26 \cf0 \
Why is it called K8s?
\f1\b0 \uc0\u8232 Because there are 
\f0\b 8 letters between \'91K\'92 and \'91s\'92
\f1\b0  in the word "Kubernetes".\
\
Kubernetes architecture is divided into two main parts:\
\

\f0\b 1. Control Plane (Master Node) \'96 Controls all actions\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls3\ilvl0
\f2\b0\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f0\b\fs26 API Server
\f1\b0 : Acts as the main entry point for all administrative tasks. It decides what information to process and exposes the Kubernetes API to the outside world.\
\ls3\ilvl0
\f2\fs18 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Scheduler
\f1\b0 : Works based on the information provided by the API server and schedules pods to appropriate worker nodes.\
\ls3\ilvl0
\f2\fs18 {\listtext	\uc0\u8226 	}
\f0\b\fs26 ETCD
\f1\b0 : A distributed key-value store that stores all cluster-related information in key-value format.\
\ls3\ilvl0
\f2\fs18 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Controller Manager
\f1\b0 : Manages various controllers like:\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls3\ilvl1
\f2\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f1\fs26 ReplicaSet\
\ls3\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 Replication Controller\
\ls3\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 Deployment Controller\uc0\u8232 It also supports auto-scaling by ensuring the desired number of pods are running.\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 \
\pard\pardeftab560\slleading20\partightenfactor0

\f0\b \cf0 2. Data Plane (Worker Nodes) \'96 Executes the actual workload\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls4\ilvl0
\f2\b0\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Kubelet
\f1\b0 : An agent that ensures the containers (pods) are healthy and running as expected on each node.\
\ls4\ilvl0
\f2\fs18 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Kube-proxy
\f1\b0 : A network component that manages IP addresses, routing, and basic load balancing for services within the cluster.\
\ls4\ilvl0
\f2\fs18 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Container Runtime
\f1\b0 : Responsible for running the actual containers. Common runtimes include:\
\pard\pardeftab560\pardirnatural\partightenfactor0
\ls4\ilvl1
\f2\fs18 \cf0 {\listtext	\uc0\u8226 	}
\f0\b\fs26 CRI-O
\f1\b0 \
\ls4\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f0\b\fs26 Containerd
\f1\b0 \
\ls4\ilvl1
\f2\fs18 {\listtext	\uc0\u8226 	}
\f1\fs26 Others (e.g., Docker, though it's being deprecated in Kubernetes)\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 \
\
\
}